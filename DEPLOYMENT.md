# Deployment Notes

The production site is hosted on Cloudflare using static assets and the custom domain:

https://nicolaskessler.com

## Manual Cloudflare Deployment

1. Make the desired edits to the site.
2. Verify the site locally.
3. Zip the repository contents.
4. In Cloudflare, open the portfolio Workers & Pages project.
5. Select **New deployment**.
6. Upload the site files.
7. Deploy and verify the custom domain.

No framework build command is required.
