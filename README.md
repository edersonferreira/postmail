# PostMail

PostMail is a program what you can very quickly send mails, written in plain text or markdown.

# Install

You can install PostMail with NPM, executing:

`npm install -g postmail`

# Usage

First, you need to define your mail, and your password. Run:

`postmail --config`

the prompt will ask your mail and password, only complete your credentials normally.

```
Your Email: myMail@gmail.com
Your Password: *********
```

## Plain Text

Now, you can send a email, defining the email/emails what you want to send your email, the subject, and the plain text.

`postmail --email anotherMail@gmail --subject Hello! --message like PostMail!`

## Markdown

You can create a markdown file, and send this markdown file to the PostMail, like this:

`postmail --email anotherMail@gmail --subject Hello! --file myMarkdown.md`

and the `MyMarkdown.md` can the any markdown file, with HTML tags or not, like this:

```markdown
# My Mail

I like to send mails to another persons!
```

