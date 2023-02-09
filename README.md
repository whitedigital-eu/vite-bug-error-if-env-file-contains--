<h3>Vite fatal error when using "$" symbol in .env file even if "$" is used in a variable not accessible by Vite.</h3>

See `.env` - there is a variable `VITE_FOO` which is accessible by vite and `BAR`, which is not (no `VITE_` prefix).
`BAR` ends with $ and crashes Vite when running `npm install && npm run dev`.