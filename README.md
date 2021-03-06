ââ# Welcome to HashLips đ

![](https://github.com/HashLips/hashlips_art_pixelator/blob/main/logo.png)

All the code in these repos was created and explained by HashLips on the main YouTube channel.

To find out more please visit:

[đē YouTube](https://www.youtube.com/channel/UC1LV4_VQGBJHTJjEWUmy8nA)

[đ Discord](https://discord.com/invite/qh6MWhMJDN)

[đŦ Telegram](https://t.me/hashlipsnft)

[đĻ Twitter](https://twitter.com/hashlipsnft)

[âšī¸ Website](https://hashlips.online/HashLips)

# HashLips Art Pixelator đĨ

![](https://github.com/HashLips/hashlips_art_pixelator/blob/main/banner.png)

HashLips Art Pixelator is a tool used to convert multiple images to pixelated images.

## Installation đ ī¸

If you are cloning the project then run this first, otherwise you can download the source code on the release page and skip this step.

```sh
git clone https://github.com/HashLips/hashlips_art_engine.git
```

Go to the root of your folder and run this command if you have yarn installed.

```sh
yarn install
```

Alternatively you can run this command if you have node installed.

```sh
npm install
```

## Usage âšī¸

In order to convert images into pixelated images you would need a list of images that you want to convert. Place all these images that will be converted in the `/input` directory.

Then simply run this command:

```sh
node index.js
```

All your images will be outputted in the `/build` directory.
If you want to change the ratio of the pixelation then you can update the ratio property on the `pixelFormat` object in the `src/config.js` file. The lower the number on the left, the more pixelated the image will be.

```js
const pixelFormat = {
  ratio: 5 / 128,
};
```

That's it, now you have pixelated images.

Hope you create some awesome artworks with this code đ
