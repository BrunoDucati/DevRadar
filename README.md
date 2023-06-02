<h1 align="center">Dev-Radar</h1>
<p align="center">Project of the <b>OmniStack10 week</b> using the following technologies.</p>

<p align="center">
<img alt="nodeJS" align="center" href="https://github.com/nodejs/node/blob/master/doc/changelogs/CHANGELOG_V12.md#12.14.1" src="https:// camo.githubusercontent.com/7ad6a0b6b451f6ae10f861a25db2d95c70bedbcf/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e6f64652e6a73406c 74732d31322e31342e312d696e666f726d6174696f6e616c3f6c6f676f3d4e6f64652e4a53"></img>
<img align="center" href="https://github.com/facebook/react/blob/master/CHANGELOG.md#16120-november-14-2019" src="https://camo.githubusercontent.com /a359cc1f2660d1c7ea0cfba868220122063b8497/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f72656163742d31362e31322e30 2d696e666f726d6174696f6e616c3f6c6f676f3d7265616374"></img>
<img align="center" href="https://github.com/expo/expo" src="https://camo.githubusercontent.com/f7e9bc1bfb3113eb06cac73a442e81d33983f91f/68747470733a2f2f696d672e736869656c64732e 696f2f62616467652f6578706f2d2d434c492d332e31312e352d696e666f726d6174696f6e616c3f6c6f676f3d6578706f"></img>
<img align="center" href="https://rocketseat.com.br/gostack#4" src="https://camo.githubusercontent.com/cad44929e98267411bcf61fb60b4023bd3556ef4/68747470733a2f2f696d672e736869656c6473 2e696f2f62616467652f4f6d6e69537461636b2d646f6e652d677265656e3f6c6f676f3d646174613a696d6167652f706e673b6261736536342c6956424 f5277304b47676f414141414e5355684555674141414241414141415143414d414141416f4c513954414141414c56424d56455648634578785773463058 4d4a7a584d4a78576346735573442f2f2f396a52727a5930753658683947736e396e333966794d65637930716432626a4e4a57425430574141414142485 253546c4d4132446f36303677463251414141476c4a52454655474a56646a31635777434149424c4573525533756639786f624448382b475a7755596938 693675634a7772784b452b37443047395134766c5971746d43536a6e647234436743677a6c794667664b664b43564f304c72504b6a6d69714d7847586b4 a774e6e58736b7157472b316f534d2b4253774438663239594c4e6a76782f4f51726e2b6739396f51536f4e6d7433506741414141424a52553545726b4a 6767673d3d"></img>
<img align="center" href=" https://rem.mit-license.org/" src="https://camo.githubusercontent.com/890acbdcb87868b382af9a4b1fac507b9659d9bf/68747470733a2f2f696d672e736869656c64732e696f 2f62616467652f6c6963656e73652d4d49542d626c75652e737667"></img>
</p>



## Goal

The objective of the development was to create a software that covered an application where the knowledge acquired with the javascript language was implemented in the web layer, in the mobile app and in the backend, with that I had the first contact with the language and the other frameworks, so the project started from scratch to the most complex section where users are updated in real time through the proposed technologies, thus making a great improvement in my programming practice and still having a didactic and professional gain with this platform, with that I had a high gain of knowledge and I intend to delve deeper into this stack.

## The project

### Web Version

The web version developed with React is the part where new users are allocated, the fields used are: Github user, technologies used and latitude and longitude coordinates, these coordinates are automatically acquired by the browser but you can change them. Next to it is the registered devs along with the Name, technologies, biography and the link to the dev's github, the data coming from github is obtained by [Api](developer.github.com).


![web](https://github.com/LucasCostakt/Dev-Radar/blob/master/images/webgif.gif?raw=true)

### Mobile version

The mobile layer is where there is the map with the registered developers are shown on it, the search is done through the top bar on the screen, in it the search is done by technologies, putting the technologies returns all the devs registered with them, each of the devs shows first your photo obtained by the [Api](developer.github.com) from github, when clicking on the dev appears the name and biography also coming from the api and the tecs coming from the bank, clicking again opens the github profile through a webview so you don't have to leave the app.

![mobilelight](https://github.com/LucasCostakt/Dev-Radar/blob/master/images/ezgif.com-video-to-gif.gif?raw=true)
![mobiledark](https://github.com/LucasCostakt/Dev-Radar/blob/master/images/mobiledarkgif%20(1).gif?raw=true)

## Libraries and resources used
- **Expo**: is a framework and platform for universal React applications. It's a set of tools and services built around React Native and native platforms that help you develop.
- **MongoDB**: MongoDB is a document database with the scalability and flexibility you want with the queries and indexing you need.
- **Insomnia**: Used to create HTTP requests specifying URL, payload, headers and authorization, using REST.
- **Mongodb compass community**: Manager of data stored in MongoDB.
- **Mongoose**: Library that gives access between the node
