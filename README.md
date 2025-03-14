# 👋 Hi there, I'm AlfiDev!

![GitHub followers](https://img.shields.io/github/followers/AlfiCloud?style=social)
![GitHub stars](https://img.shields.io/github/stars/AlfiCloud/cloudku-uploader?style=social)
![GitHub license](https://img.shields.io/github/license/AlfiCloud/cloudku-uploader)
![GitHub repo size](https://img.shields.io/github/repo-size/AlfiCloud/cloudku-uploader)

## 🚀 About Me

I'm a passionate developer who loves creating efficient and powerful tools for developers. I'm the creator of [CloudkuImages](https://cloudkuimages.com) and the author of **cloudku-uploader**, an NPM package designed for seamless file uploads.

## 🛠️ My Projects

### 🌩️ Cloudku Uploader

[![NPM Version](https://img.shields.io/npm/v/cloudku-uploader)](https://www.npmjs.com/package/cloudku-uploader)
[![Downloads](https://img.shields.io/npm/dt/cloudku-uploader)](https://www.npmjs.com/package/cloudku-uploader)

A powerful Node.js package that allows developers to easily upload files to CloudkuImages.

```bash
npm install cloudku-uploader
```

#### 🔧 Usage

```javascript
const cloudkuUploader = require('cloudku-uploader');

async function upload() {
    let result = await cloudkuUploader.uploadFile(Buffer.from("Hello, world!"), "hello.txt");
    console.log(result);
}
upload();
```

📌 Learn more in the [documentation](https://cloudkuimages.com/docs).

## 🌐 Connect with Me

- GitHub: [AlfiDev](https://github.com/AlfiCloud)
- Website: [CloudkuImages](https://cloudkuimages.com)
- NPM: [cloudku-uploader](https://www.npmjs.com/package/cloudku-uploader)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

