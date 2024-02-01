# How To Use EJS to Template Your Node Application

Repository used as a backup of files while looking at a [guide](https://www.digitalocean.com/community/tutorials/how-to-use-ejs-to-template-your-node-application) on DigitalOcean

<hr />

### Introduction
When quickly creating Node applications, a fast way to template your application is sometimes necessary.

[Jade](jade-lang.com) comes as the [default template engine for Express](https://expressjs.com/en/guide/using-template-engines.html) but Jade syntax can be overly complex for many use cases.

[Embedded JavaScript templates (EJS)](https://ejs.co/) can be used as an alternative template engine.

In this article, you will learn how to apply EJS to an Express application, include repeatable parts of your site, and pass data to the views.

### Prerequisites
If you would like to follow along with this article, you will need:
- A local development environment for Node.js. Follow How to Install Node.js and Create a Local Development Environment.

This tutorial was originally written for express v4.17.1 and ejs v3.1.5. It has been verified with Node v16.0.0, npm v7.11.1, express v4.17.1, and ejs v3.1.6.
