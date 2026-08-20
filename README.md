# Premier League Predictor - Supabase Connection Test

Minimal test frontend for Supabase anonymous authentication, competition password access, RLS, and team loading.

## Upload to GitHub

Upload `index.html` and `styles.css` to the root of the `premier-league-predictor` repository.

## Test

1. Open the deployed site.
2. Anonymous session should turn green.
3. Try an incorrect password: access should be denied.
4. Try the correct password: access should be granted.
5. Team count should show 20.
6. Refresh: the anonymous session and competition membership should persist.

Never commit the Supabase secret/service-role key or database password.
