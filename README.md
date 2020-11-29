# GoMarketplace - Mobile ecommerce simulation application

## What was done:
Application that presents products in its catalog, these products coming from a fake api being served 
with json-server, has the functionality of adding the products to the shopping cart and increasing the 
quantity and decreasing the quantity of the same product that will be purchased, shows in footer of the 
application the quantity of products in the cart and the total price of the sum of the total products 
in the shopping cart.

## Used tecnologies:
- React Native;
- React Hooks;
- Styled components;
- Json Server.

## To make it work:
- As the application is running on a physical device then we will have to put the ip of the machine 
on which the application will run, in place of the word localhost, in the api.ts file located in the service folder;
- Turn on the json-server to serve the fake api containing the products. In this command you will also have the same 
ip informed in the api.ts file after the --host flag:
**yarn json-server --host 192.168.15.8 -p 3333 --watch server.json**;
- To build the project and connect it to an emulator or android physical device just type in the terminal:
**yarn android**;
- To build the project and connect it to an emulator or ios physical device just type in the terminal:
**yarn ios**;
- If after the build is done and the metro bundler does not start, then in the application folder with the terminal, type:
**yarn start**.

<img src="https://github.com/LucasBarbosaFonseca/AppGoMarketplaceReactNative/blob/master/imagesApp/img1.jpeg" width="250">
<img src="https://github.com/LucasBarbosaFonseca/AppGoMarketplaceReactNative/blob/master/imagesApp/img2.jpeg" width="250">
