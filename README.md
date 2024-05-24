
## run locally

to run the site locally:

1. **install live-server**:
   ```sh
   npm install -g live-server
   ```

2. **run live-server**:
   navigate to your project root and run:
   ```sh
   npx live-server dist --entry-file=index.html
   ```

this will start a local server and open your default browser to `http://127.0.0.1:8080`.

## making changes

1. **make changes**: update your files in the `src` folder.
2. **rebuild**: after making changes, run the following commands to update the `dist` folder:
   ```sh
   npm run build:css
   cp src/index.html dist/
   cp -r src/js dist/
   ```

