<!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>My GitHub-style Markdown Page</title>
        <link rel="stylesheet" href="path/to/github-markdown.css">
        <style>
            .markdown-body {
                box-sizing: border-box;
                min-width: 200px;
                max-width: 980px;
                margin: 0 auto;
                padding: 45px;
            }
            @media (max-width: 767px) {
                .markdown-body {
                    padding: 15px;
                }
            }
        </style>
    </head>
    <body>
        <article class="markdown-body">
            <!-- Your rendered Markdown HTML goes here -->
            <h1>My Awesome Project</h1>
            <p>This is a paragraph with some <strong>bold text</strong> and <em>italic text</em>.</p>
            <pre><code>console.log("Hello, GitHub-style!");</code></pre>
        </article>
    </body>
    </html>
