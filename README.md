# Intro

Makerskiff is a portable 104hp Eurorack skiff. It's made to be affordable (<150€) and cut on a laser cutter.
It's derivated from <a href="http://nonlinearcircuits.com">Nonlinearcircuits</a>'s <a href="https://www.thingiverse.com/thing:1206319">Eurorack Laser Cut Case</a>.

# Build

### Wood

Makerskiff is made for 3mm wood. When you send the file for cutting, please make sure that each of the joing tabs are 3mm long, to make sure there were no scaling up or down of the file while exporting/converting/downloading and what not. If it's not, just scale it back to the good size !

When you have the pieces, just glue them together ! Varnish, sand, paint, do whatever you want until you like it.

### PSU

The case is intended to be built with the <a href="https://www.meanwell-web.com/content/files/pdfs/productPdfs/MW/Rt-65/RT-65-spec.pdf">Mean Well RT-65B</a>.

The space for it is <strong>tight</strong> in the way I positioned it, but it should work. I made it work. There less than a centimiter to make the cables go from the terminals to the busboard and the AC inlet.

I highly recommend you cover the terminals with a bit of electrical tape as some of these will be carrying the mains and the RT-65B doesn't have a proper plastic cover.

### Busboard

The busboard is a Moraydular Power Bus (Wide Version). Find all the info on that one on the dedicated GitHub repo : https://github.com/vaeinoe/moraydular/tree/master/powerbus

PCB's are available at https://pushermanproductions.com 

### BOM

* 1x Mean Well RT-65B
<br><small><i>Mouser part No: 709-RT65B</i></small>
* 2x Gie-Tec 104hp vector rails <strong>with lip</strong>
* 1x Schurter DD11.0114.1110 AC Power Inlet
<br><small><i>Mouser part No : 693-DD11.0114.1110</i></small>
<br><small><i>Careful, they're often sold without the fuse drawer. Remember to include it in your order ! You might want to add a cover as well. If you want to save a bit, you can also wrap it with electrical tape when it's mounted.</i></small>
* Busboard's BOM to be found on the dedicated <a href="https://github.com/vaeinoe/moraydular/tree/master/powerbus">GitHub Repo</a>.
* Various cables and screws, I'm sure you can figure that part out.

# Photos

Coming soon-ish

# License
This project is licensed under the <a href="https://creativecommons.org/licenses/by-nc-sa/3.0/" target="_blank">Creative Commons - Attribution - Non-Commercial - Share Alike</a> license.
