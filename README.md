# redesigned-telegram
if (   event === "issue_comment" &amp;&amp;   action === "created" &amp;&amp;   body.comment.body.startsWith("/chatgpt") ) {   const prompt = body.comment.body     .replace(/^\/chatgpt\s*/i, "");    // Send prompt to your AI backend   // Generate response   // Post response back to GitHub }
