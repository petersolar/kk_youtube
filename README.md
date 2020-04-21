# Youtube element

This KC custom element allows you to add various types of youtube video url, it extracts the video id for your apps and shows the video.

![screenshot](https://amend.cz/youtube/youtube2.png)

## Setup

1. Deploy the code to a secure public host
   - See [deploying section](#Deploying) for a really quick option
1. Follow the instructions in the [Kentico Kontent documentation](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features#a-3--displaying-a-custom-element-in-kentico-kontent) to add the element to a content model.
   - The `Hosted code URL` is where you deployed to in step 1
   - Pass the necessary parameters as directed in the [JSON Parameters configuration](#json-parameters) section of this readme.

## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your GitHub account as well.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/hzik/kc_youtube/)

## Configuration

You can specify the Parameters {JSON} part of the configuration to configure the default state or a lable.
Possible configurations:

```json
{
    "width": 800,
    "height": 600
}
```
