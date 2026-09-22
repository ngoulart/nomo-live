# NOMO motion: live dashboard

The live dashboard of the NOMO sleep study's motion app, as a static page. It holds no data and no secret: it reads the study server's `/live` route with the token given in the address (`?k=`), and the server answers nothing without it. Generated from `tasks/A11_motion_pull/server/dashboard.html` by `supabase/make_dashboard.py`; published by `supabase/publish_dashboard.sh`.
