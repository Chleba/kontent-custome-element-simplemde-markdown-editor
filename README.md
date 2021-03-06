# SimpleMDE Markdown editor Custom Element for Kentico Kontent

This is a [custom element](https://kontent.ai/learn/tutorials/develop-apps/integrate/content-editing-extensions) for [Kentico Kontent](https://kontent.ai) that allows users to author Markdown using the SimpleMDE editor.

![Screenshot of custom element](SimpleMdeMarkdownEditor.gif)

## Setup

1. Deploy the code to a secure public host
    * See [deploying section](#Deploying) for a really quick option
1. Follow the instructions in the [custom elements documentation](https://kontent.ai/learn/tutorials/develop-apps/integrate/content-editing-extensions#a-displaying-your-custom-editor-in-kontent) to add the element to a content model.
    * The `Hosted code URL` is where you deployed to in step 1
    * No additional configuration required.

## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your GitHub account as well.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Kentico/kontent-custome-element-simplemde-markdown-editor)

## What is Saved?

The value is a string of Markdown text.

## Contributors

Originally contributed by [@petrpyszko](https://github.com/petrpyszko)
