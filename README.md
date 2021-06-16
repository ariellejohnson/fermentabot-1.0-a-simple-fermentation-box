# simple-fermentation-box:
## the $165 plug-n-play fermentation incubator
a super simple, no wiring required, controlled environment which I use to incubate fermentations.

This design became the basis for [the fermentabot](https://github.com/OpenAgInitiative/fermentabot)**, a more complex, not necessarily finished or stable, fermentation device.

this is a box I developed for making koji and other temperature-sensitive fermentations. The main goals were relatively stable temperature control, inexpensive and cleanable materials, and simple construction, avoiding wiring a PID box. 

This project took me about 30 minutes to make a quick-n-dirty, plug-n-play incubator.

![](/photos/IMG_0766.jpg)

Senses: Temperature, humidity
Actuates: Heating, humidification

*The housing:* I use an 18" x 26" x 12" lexan container (made by cambro) with lid. Found in restaurant walk-ins the world over. Food-grade, rugged, easy to clean.

![](/photos/IMG_0761.jpg)

*The controller:* the most expensive component. Not truly a PID box (this is a thermostat, it works on a different algorithm; in truth, the algorithm is turn the actuator on when the setpoint is too low and turn it off when the setpoint is reached.) PID controllers are great! I highly recommend them. But since they involve wiring a temperature sensor and heating actuator, they are beyond the scope of this design. 

*The heater:* waterproof, even heating. Not as nice as circulating heated air, but it works.

*The humidifier:* a cheap and cheerful humidifier, designed for running in your car or at your desk. Works nicely in a small space.

*The insulation:* I don't use a styrofoam cooler, they are hard to clean and they tend to off-gas when heated. They can melt in contact with a heating element. Instead, this uses Reflectix, a nifty, thin, flexible insulation to make a jacket for your lexan housing.

![](/photos/IMG_0448.jpg)

**Directions:**

make a jacket for the lexan (#1 on BOM) out of reflectix (#8 on BOM) and reflective insulation tape (#9 on BOM). Fit at least the sides, or sides and bottom, if you want to be more precise. I usually trim the reflectix to the height of the food storage container, and cut this to a little wider than each side, then overlap the ends and tape to fit the sloping sides of the container. Cut another piece that fits the lid. Don't tape the reflectix directly to the plastic housing, so that you can remove the jacket as necessary.

![](/photos/IMG_0492.jpg)
![](/photos/IMG_0493.jpg)

unroll the heating mat (#5 on the bill of materials (BOM)) and put it in the bottom of the lexan container (#1, cambro polycarbonate food storage box, on BOM). Put the drain trays (#3 on BOM) on top of the heating mat. Put the humidifier (#6 on BOM) inside the box as well. Fill it with water, insert a wick into the cap, and cap it, first.

Plug in the humidity and temperature controller (#4 on BOM) and plug in the heating mat and humidifier (using the USB cable and USB to AC adapter). Set the temperature and humidity to your desired range.

I have used 32C and 85% humidity to produce koji, in the past.

I usually place a temperature/huidity probe on the surface of whatever's fermenting. This size box can hold 2-3 half size perforated hotel pans for incubating koji. I put the probe nestled into the inoculated koji of the lowest tray. This one gets the most heat, so I rotate the position of trays in the stack every 4 hours (taking a break overnight). 


Liability

In plain language: don't be stupid, be realistic about the limits of your knowledge, educate yourself about what you're doing, familiarize yourself with food safety guidelines, take a risk- and harm-reduction attitude towards experimentation, and fucking make sure whatever you've made is safe before feeding it to anyone or selling it. These are your responsibilities in using this or any other equipment to make fermented foods.

Any type of fermentation involves some level of risk. By using this design, you assume all responsibility for educating yourself on the food safety guidelines for fermentation, familiarizing yourself with potential hazards, for any negative or unsafe results, for disposing of any potentially hazardous products produced with the design, and for ensuring d=safety and quality before you consume any products or serve them to others. I am not a food safety expert or microbiologist, and I can't give you professional, medical, regulatory, or legal advice on food safety. 

This temperature controlling unit must be used according to the manufacturer's instructions and only for the specific purpose for
which it was designed. Arielle Johnson shall not and is not responsible or liable for any consequential damages, injuries, paralysis, or death arising from the use or misuse of the products based on this design. By using this design, you(the user) and your heirs assume all responsibility of ownership, risks of use, and agree to hold harmless, Arielle Johnson and heirs for any damage, incident, or action, involving the design, included but not limited to illness resulting from fermented products made with the design. 
