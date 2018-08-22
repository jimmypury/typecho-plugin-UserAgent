# typecho-plugin-UserAgent

A plugin for typecho to display UserAgent of comments.

## Usage

1. Enable this plugin.
2. Put `<?php UserAgent_Plugin::render($comments->agent);?>` into your theme code.

*Pay attention to the operation order, or your website will display `Server Error`! (Tell the truth I'm too lazy to write a judge.)*