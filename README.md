# Image Embed on Discord

This Cloudflare Worker script lets you share your images on Discord in a cool way.

## How to Use

1. **Create the Cloudflare Worker:**
   - Create a new Cloudflare Worker.
   - Open the **Quick Edit** section and paste the code from your `main.js` file into the code window.

2. **Configure the Script:**
   - Replace `Your_title_here` with a title of your choice.
   - Replace `Description_for_your_image` with a description of your choice.
   - Replace `cloudflare_worker_link` with the URL of your Cloudflare Worker.
   - Replace `#00FF8E` with the hex color code of your choice.

   *Example:*  
   If your worker link is `https://test.example.workers.dev`, replace `cloudflare_worker_link` with that URL.  
   If you have a custom domain, use your custom domain instead.

3. **Using the Worker:**
   - Visit your Cloudflare Worker URL (e.g., `https://test.example.workers.dev`).
   - Append the query parameter `?url=imagelink` to the URL.
   
   *Example:*  
   `https://test.example.workers.dev?url=https://i.imgur.com/eucAMTA.png`

   This will display the image and, when the link is sent on Discord, it will show a cool embed with the image.
