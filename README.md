# Yi Jing Bot
<img width="293" alt="resim" src="https://user-images.githubusercontent.com/61288822/230892627-a0cd3dcc-ecbe-404a-b465-ca57a4d67671.png">

Discord bot that does your Yi Jing reading.

To run locally, create a [Discord application/bot](https://discord.com/developers/applications) and fill in the required environment variables in the `.env.template` file and rename it to `.env`. 

```
npm install 
node deploy-commands.js
node index.js 
```


Use `/read` to get your hexagram(s). 

`/fullread` will give you an opinionated reading.


### Credits

[I Ching CLI](https://github.com/abbeymondshein/i-ching-cli) for the traditional calculations to get the hexagrams.
