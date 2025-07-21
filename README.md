# led_reaction_game
This is a cool game developed that uses about 35 leds, one rp2040 and 20 mx switches and keycaps. Now how does this game work? There are 4 players, each with 5 buttons. Once the game starts all leds will start turning random colors, after a random amount of time (3-15 sec) all the leds will turn one of 5 colors. Every of the 5 buttons has one color assigned to it, the player who can press the button corrosponding to the right color wins! Its pretty much a cool reaction game.
# PCB
This is the schematic (the actual leds arent on the pcb as I will be using a led strip, theyre just included here so you can see how they will be wired.)

<img width="1342" height="806" alt="log schematick with leds" src="https://github.com/user-attachments/assets/a58513b5-4b9a-411c-bd06-4dde397fbb36" />

The PCB looks like this(see, without the leds just the buttons and diodes):

<img width="730" height="691" alt="image" src="https://github.com/user-attachments/assets/8e9dc57b-4159-46ea-994a-0060faf77d53" />

The PCB is in a square format, as thats how the players will sit.

# CAD
Now moving to the CAD, this case was designed in Fusion 360 and is a pretty simple case, it consists of 2 parts, top and bottom.

<img width="982" height="608" alt="image" src="https://github.com/user-attachments/assets/e40b2af0-926e-41d4-8037-95d6777481b4" />

As you see a hole has been left out for the USB cable.

<img width="714" height="653" alt="image" src="https://github.com/user-attachments/assets/a04774c9-4d2f-4bce-b308-44a8e07d938b" />

You can see on the bottom right I left a slit to put the neopixels trough, as they will be put on the top of the case (with glue or some come with the backside being sticky and if thats the case ill just stick it on there) You can also see I am using 4 m4 screws to hold the things together.

# Firmware
The Firmware has been used to make this game (you can download it in the production or the Firmware folder)
ATTENTION! Firmware has been made with AI!

# BOM
20 MX switches / Required: YES / COST: 6$ / LINK: https://de.aliexpress.com/item/1005007503045573.html?src=google&pdp_npi=4%40dis!EUR!0.84!0.49!!!!!%40!12000045838558309!ppc!!!&src=google&albch=shopping&acnt=615-992-9880&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=_oFgTQeV&gclsrc=aw.ds&&albagn=888888&&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=de1005007503045573&ds_e_product_merchant_id=109387492&ds_e_product_country=AT&ds_e_product_language=de&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=22482375352&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=22482428299&gbraid=0AAAAA_TvRHoTGdR4i_oGu_wm5WH3zjW4T&gclid=Cj0KCQjwyvfDBhDYARIsAItzbZEzCHXCu7azNIC0y4GsZ6CIIDBcuycMG-0dvdB0Wm8gSBOsYiDgOgYaAqBaEALw_wcB

20 blank white Keycaps / Required: YES/ COST: 3$ (for now it could go up) / LINK: https://www.aliexpress.com/p/trade/confirm.html?objectId=1005007360781736&from=aliexpress&countryCode=AT&shippingCompany=CAINIAO_STANDARD&provinceCode=901700010000000000&cityCode=901700010003000000&aeOrderFrom=main_detail&skuAttr=200007763%3A201336100%3B14%3A865%23129%20white&skuId=12000040422881428&skucustomAttr=&quantity=1&spm=a2g0o.detail.0.0&curPageLogUid=1753119490499_MMSE66&pdpBuyParams=%7B%7D

20 Diodes / Required: YES / COST: 5$ / Link: https://www.aliexpress.com/p/trade/confirm.html?objectId=1005005977345646&from=aliexpress&countryCode=AT&shippingCompany=CAINIAO_FULFILLMENT_STD&provinceCode=901700010000000000&cityCode=901700010003000000&aeOrderFrom=main_detail&skuAttr=14%3A365458%23BAT54C%20(KL3)&skuId=12000035140049245&skucustomAttr=&quantity=1&spm=a2g0o.detail.0.0&curPageLogUid=1753119549514_hhS7EV&pdpBuyParams=%7B%7D

3d printing Filament / Required: Yes / Cost: 10$ (for now it could change) / Link: https://de.aliexpress.com/item/1005008747223521.html?spm=a2g0o.productlist.main.24.71b2e839utG4Dp&algo_pvid=afe66706-778b-4907-93f3-27c8b274a733&algo_exp_id=afe66706-778b-4907-93f3-27c8b274a733-23&pdp_ext_f=%7B%22order%22%3A%221568%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%2125.21%216.32%21%21%2128.60%217.16%21%4021039a5b17531196428298880e5243%2112000046499569556%21sea%21AT%216396215576%21ABX&curPageLogUid=42qWHD5TjOAE&utparam-url=scene%3Asearch%7Cquery_from%3A

M2 screws / Required: Yes / Cost: 8$ / Link: https://de.aliexpress.com/item/1005007159750547.html?spm=a2g0o.productlist.main.1.5eb3167aoNl5ZI&algo_pvid=4df4c264-cbff-4d37-a114-0ee31f974b47&algo_exp_id=4df4c264-cbff-4d37-a114-0ee31f974b47-0&pdp_ext_f=%7B%22order%22%3A%222160%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%215.80%210.87%21%21%216.58%210.99%21%402103834817531197157033412e73d3%2112000039655872513%21sea%21AT%216396215576%21ABX&curPageLogUid=Youa65Y32Dvi&utparam-url=scene%3Asearch%7Cquery_from%3A

Neopixel leds / Required: YES / COST: 4$ / Link: https://de.aliexpress.com/item/1005007982624217.html?spm=a2g0o.productlist.main.4.2ae23767rbIS0y&algo_pvid=d275a318-507f-4324-94a4-05384be748f8&algo_exp_id=d275a318-507f-4324-94a4-05384be748f8-3&pdp_ext_f=%7B%22order%22%3A%223191%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%211.63%210.87%21%21%2113.26%217.07%21%402103919917531205886286177e34f8%2112000043170571838%21sea%21AT%216396215576%21ABX&curPageLogUid=E7d53sA4rKzR&utparam-url=scene%3Asearch%7Cquery_from%3A&_gl=1*3spku5*_gcl_aw*R0NMLjE3NTMxMjA1ODIuQ2owS0NRand5dmZEQmhEWUFSSXNBSXR6YlpHM1daS3ZNR3RVQkNiR0ZzbnNJTWVnWV9TaldQaTRsS3RDSE1zRE1XQVFDOXk4SjhleHp5NGFBbFpjRUFMd193Y0I.*_gcl_dc*R0NMLjE3NTMxMTk2MzYuQ2owS0NRand5dmZEQmhEWUFSSXNBSXR6YlpHbDh6eHhIYy13ZEdIMUd3R1E3SkZqYVItTXotbGd1Q2lJU2lIWXptcFRyR2FwR0ZwM0N0b2FBZ0tURUFMd193Y0I.*_gcl_au*Njc0NTUzMDIxLjE3NTExMDk5ODA.*_ga*MTk3MjI5MDc1Ny4xNzQyMDY0MDI4*_ga_VED1YSGNC7*czE3NTMxMTkzNDckbzIwJGcxJHQxNzUzMTIwNTgxJGo2MCRsMCRoMA..

PCB cost: 30$ (with 20$ coupon from hackclub) / Required: YES

Total cost of BOM: 52$ (some items are currently discounted for me so could change)


