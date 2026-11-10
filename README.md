# Healing Steps — Καρτέλα (Αλέξανδρος Τσανίδης)

Αντίγραφο της εφαρμογής Healing Steps v5.0 με δική μας βάση Supabase (`healing-steps`, eu-central-1) και νέο σήμα.

- `index.html` — όλη η εφαρμογή (ένα αρχείο)
- `supabase/schema.sql` — πίνακες, κανόνες πρόσβασης (RLS), RPC, storage
- `supabase/functions/hs-gcal` — συγχρονισμός με Google Calendar (θέλει secret `GOOGLE_SA_JSON`)

Τα δεδομένα ασθενών ΔΕΝ είναι σε αυτό το repo — μόνο στη βάση, και τα βλέπουν μόνο τα μέλη του ιατρείου.
