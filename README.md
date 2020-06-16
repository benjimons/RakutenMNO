# RakutenMNO
Instructions on how to enable Rakuten Mobile Network ([Rakuten MNO](https://network.mobile.rakuten.co.jp)) on iPhone X and similar, this is NOT for the Rakuten MVNO network but for the new 4G network.

It is only tested on iPhone X but should work for iPhone 6 and up

These instructions are written for ***Windows PC.***

Japanese instructions can be found here - https://kakuyasu-sim.jp/iphone-6s-7-8-and-plus-rakuten-unlimit

This is not officially supported by Rakuten but I have tested it and working on iPhone X which at the time of writing is not officially supported - https://network.mobile.rakuten.co.jp/product/byod/?l-id=certified-products_product_byod

## Steps
1. Install iTunes
2. Download the Docomo ipcc file (you can download from this repository teste working with IOS 13
3. Install the Rakuten SIM into the iPhone you want to use
4. Execute the following command from the command line/cmd
   <pre>iTunes.exe /setPrefInt carrier-testing 1</pre>
5. Connect your iPhone to your PC using a standard iPhone cable
6. Hold down Shift while clicking Restore iPhone
   ![alt text](https://github.com/benjimons/RakutenMNO/blob/master/itunes7.png)
7. Locate the Docomo IPCC file (Docomo_jp.bundle.ipcc - [download here](https://github.com/benjimons/RakutenMNO/raw/master/Docomo_jp.bundle.ipcc))
   ![alt text](https://github.com/benjimons/RakutenMNO/blob/master/itunes8.png)
8. Once installed, restart the iPhone
9. Ensure you have 4G VOLTE turned ON in the carrier settings of the iPhone
10. Using your iPhone on WiFi download the following mobile config profile - [click here](https://github.com/benjimons/RakutenMNO/raw/master/RakutenMNO.mobileconfig))
11. Follow the onscreen instructions advising you how to install the profile
11. You should now get service and it should be working for Calls, SMS and Internet.
