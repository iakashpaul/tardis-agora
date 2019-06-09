# TARDIS | Agora.io Challenge

## Team : Taha K, Akash Paul

## About

We've used Agora.io stack to help people learn, instruct others & participate in immersive AR experiences without requiring costly hardware & delivered via a webpage for PC/Android browsers. Selling hosting & add-ons would be another way for developers to create more use cases with our product by incorporating human pose detection data which is being performed on the device itself

- Youtube: [https://youtu.be/sN4ITLhJ5zs](https://youtu.be/sN4ITLhJ5zs)

- Github: [https://github.com/tardis-agora](https://github.com/tardis-agora)

- Demo: [https://tardis-agora.surge.sh](https://tardis-agora.surge.sh)

## Steps to run

- Clone this repo & cd into it

- Install node.js & run, `npm install --global surge`

- Run, `surge`& provide a domain of your choosing

- Voila, it is going to be hosted at your subdomain on surge.sh, visit it over https

## Modules used,

- Agora.io, [Token Server for Agora](https://github.com/AgoraIO-Community/TokenServer-nodejs) on heroku at [https://tardis-demo.herokuapp.com/access_token?channel=test&uid=1234](https://tardis-demo.herokuapp.com/access_token?channel=test&uid=1234)

- TensorFlow.js, [PoseNet Model for realtime human pose detection](https://github.com/ml5js/ml5-examples/tree/release/javascript/PoseNet)

- Materializecss for themeing, jQuery for helping with JS.