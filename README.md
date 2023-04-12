<p align="center" width="200">
   <img align="center" width="100" src="https://raw.githubusercontent.com/BraianVaylet/buildspace-epic-game-ui/main/public/wizard.png" />
</p>

# 🧙‍♂️ Epic Games [UI]

The project is deployed in Vercel so that you can see it and interact with it, any criticism or comment is appreciated, you can access the demo at the following link:

## About the project

Web project based on web3 developed with **[Next.js](https://nextjs.org/)** and **[ChakraUI](https://chakra-ui.com/)**. In this application, users will be able to play a small game where they will have to coin their own NFT character which they will then use to try to defeat the boss together with other players, the entire process will be stored within the blockchain.

For this it is necessary to first authenticate using the wallet **[Metamask](https://metamask.io/)** and configuring it to use the test network.

Users will be able to mint their NFTs, for this it is necessary to pay the transaction using BNB. Since we are on the Bsc testnet we will not be using real BNB, but rather test ones. To load balance to your wallet and thus have BNB to use in the BSC testnet, you can use the following **[link](https://testnet.binance.org/faucet-smart)**. They will also need BNB to be able to attack the boss.

The rules of the game are quite simple, each character has three attributes, these are:

| attribute | Description |
| -- | -- |
| ❤ | character hp |
| ⚔ | damage on attack |
| 🛡 | defense |

I present to you the characters of this saga: (the characters were created in [Hero Forge](https://www.heroforge.com/))

<table>
   <tr>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/FJ5lUgJ.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>150</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>50</td>
            </tr>
         </table>
      </td>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/CmYArzl.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>150</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>50</td>
            </tr>
         </table>
      </td>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/BvpPiRE.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>200</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>0</td>
            </tr>
         </table>
      </td>
   </tr>
   <tr>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/3XGEHQh.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>100</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>100</td>
            </tr>
         </table>
      </td>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/v0W6GOD.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>50</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>150</td>
            </tr>
         </table>
      </td>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/Ld5Ra2j.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>100</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>100</td>
            </tr>
         </table>
      </td>
   </tr>
   <tr>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/Sqa43qp.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>50</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>150</td>
            </tr>
         </table>
      </td>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/L2QcAbi.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>150</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>50</td>
            </tr>
         </table>
      </td>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/2fC9ewH.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>100</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>100</td>
            </tr>
         </table>
      </td>
   </tr>
   <tr>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/pn0iaKf.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>50</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>150</td>
            </tr>
         </table>
      </td>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/zT8ObmD.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>150</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>50</td>
            </tr>
         </table>
      </td>
      <td>
         <img
            align="center"
            width="200"
            src="https://i.imgur.com/eyG6FgJ.png"
         />
         <table width="250" border="1px solid black">
            <tr>
               <th>Attribute</th>
               <th>Description</th>
            </tr>
            <tr>
               <td>❤</td>
               <td>1500</td>
            </tr>
            <tr>
               <td>⚔</td>
               <td>50</td>
            </tr>
            <tr>
               <td>🛡</td>
               <td>150</td>
            </tr>
         </table>
      </td>
   </tr>
</table>

Keep in mind that defense is a bonus that your character has since the boss does not have that privilege, although if we see his hp points we are facing an enemy that is very difficult to take down.

I present to you the first boss of this saga, it is Big Kangh.

<div>
   <img
      align="center"
      width="200"
      src="https://i.imgur.com/jBQ57F5.png"
   />
   <table width="250" border="1px solid black">
      <tr>
         <th>Attribute</th>
         <th>Description</th>
      </tr>
      <tr>
         <td>❤</td>
         <td>120000</td>
      </tr>
      <tr>
         <td>⚔</td>
         <td>200</td>
      </tr>
      <tr>
         <td>🛡</td>
         <td>0</td>
      </tr>
   </table>
</div>

To attack the boss you first need to choose a power, you can select one of these three: 🔥 fire, 💧 water and 🌿 vegetation. Each of them is good against 1 but weak against another.

<p width="400">
   <img align="center" width="250" src="https://raw.githubusercontent.com/BraianVaylet/buildspace-epic-game-ui/main/public/powers.png" />
</p>

Every time we select a power and attack the boss the boss will also select one of them, the winner will have the chance to attack and cause damage to the other.

Remember that the boss has a lot of hp and your character doesn't, so invite your friends so that together you can defeat him! 😁

This was a 100% academic project while I was taking the courses on the platform **[buildspace](https://buildspace.so/)**, which I recommend to any developer who wants to start developing for web3.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
