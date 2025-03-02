# Tool Trolley

Possible Names: "Handlanger" (Afrikaans, brand), "Benchman" (english, brand)

Different Models kan have names like "Sidekick", "Henchman"

Work on a second iteration of the tool trolley.

Idea is to build it in two or three parts:

## Top (Tool Chest)

Tool Chest with handles and drawers (at least 3x 75mm), with rubberized top surface, very sturdy.

Big Drawer maybe 75mm, smaller drawers the height of 1/2" sockets (35 or 40mm), use 35mm runners (should not load too much weight into a drawer to start with)

Get weight of Gedore Tool box loaded with tools, also look at Gedore 3 drawer tool box

Integrate a lightweight vice (100mm jaw), possibly using a G-Clamp, t-track? Drill press vice on t-track? Can be stored in drawer or side?

### Handle

Make foldable in between the square tubing on the short sides (next to the drawers). Make possible to be locked into open/closed positions

### Drawers

Must be Lockable! See if there is a way to ensure only one drawer is open at a time, having more than one open may cause the trolley to tip over

## Middle

Frame, build in levelers here that pushes out to the base (all electronics and mechanisms will be here). Possibly make separate left and right sides (much more compact to transport)

## Bottom (Dolly)

Separate Component, possible different configurations with feet and "auto-leveling" pins.

Maybe integrate Nose-Trolley/Hand-Truck. This part is kind of like a dolly

## Dimensions

Suggested Dimensions 600x450x900, possibly scale down to 450x450

Tool Trolley V1 Dimensions 826x477x902

[Mastercraft 6 Drawer Tool Chest](https://www.mastercrafttools.co.za/product/6-drawer-tool-chest/)
720x370x435mm

## Auto Leveling

[T16 Leadscrew](https://www.aliexpress.com/item/1005007629566407.html?spm=a2g0o.productlist.main.7.59e16qwc6qwcVb&algo_pvid=7c3e6f33-cfc5-45ec-93a8-5e35849617dd&algo_exp_id=7c3e6f33-cfc5-45ec-93a8-5e35849617dd-6&pdp_ext_f=%7B%22order%22%3A%221%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%2117.83%214.91%21%21%21129.41%2135.67%21%40%2112000041566476603%21sea%21UK%210%21ABX&curPageLogUid=3lSsUMBG3zZU&utparam-url=scene%3Asearch%7Cquery_from%3A)

Make with about 150mm adjustment (may be able to work on stairs)

Electronics with Raspberry Pi Pico (enough PWM pins to drive 4 steppers which needs 2 PWM pins per stepper, steppers also need separate drivers), use [6DOF sensor](https://www.robotics.org.za/GY-521?search=6dof) for leveling

[Nema 17 Steppers](https://www.robotics.org.za/17HS3401?search=nema17) to drive rods

Battery Bank, make USB + USB-C Availalbe to charge items like phone [Xiaomi 20000mah](https://www.takealot.com/xiaomi-redmi-20-000mah-18w-fast-charge-power-bank-black/PLID72768095), check if other options are available with correct voltages needed by the steppers etc. Power Tool Battery?

Able to convert to manual leveling at cost saving
