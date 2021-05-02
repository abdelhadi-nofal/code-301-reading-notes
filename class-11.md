## What is EJS?

EJS is a template system. You define HTML pages in the EJS syntax and you specify where various data will go in the page. Then, your app combines data with the template and "renders" a complete HTML page where EJS takes your data and inserts it into the web page according to how you've defined the template. For example, you could have a table of dynamic data from a database and you want EJS to generate the table of data according to your display rules. It saves you from the drudgery of writing code to dynamically generate HTML based on data.

EJS is compatible with Express for back-end use as it hooks into the View engine architecture that Express provides and lets you render web pages to the client with res.render() in Express.

FYI, there are dozens of competing template systems for use in node.js. EJS is a popular one and people typically choose one based on features that match your needs, how their layout language fits what you want to use, what seems easiest to you to use, etc... I've used Pug, Handlebars, Nunjucks and EJS. Nunjucks is my current favorite.

EJS (along with all the other competing template engines) allows you to generate full-blown HTML pages which certainly enables a "proper front-end".

EJS is a tool for generating web pages that can include dynamic data and can share templated pieces with other web pages (such as common headers/footers). It is not a front-end framework. While EJS can be used by client-side Javascript to generate HTML on the client-side, it is more typically used by your back-end to generate web pages in response to some URL request. EJS is not a client-side framework like Angular or React and does not dictate what client-side framework you do or don't use (if any). It is mostly covers a separate solution space.

