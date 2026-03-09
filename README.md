# Masterpiece_Market-
My Art Marketplace / Social Platform

This is my project for an art marketplace where artists can post listings, upload images, get quotes, likes, reshares, comments, verifications, payments, and forecasts.

Built with:
- Supabase (database, auth, storage, Edge Functions)
- Planning Next.js frontend + Vercel deployment

## What's in this repo right now
- supabase/exported_create_tables.sql → backup of table structures
- edge-functions/ → code for the three Edge Functions (estimate_price, marketplace-online, marketplace-forecast)
- supabase/storage_info.md → note about image bucket

More coming soon: frontend pages, RLS export, foreign keys.
