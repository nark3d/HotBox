# HotBox

HotBox - a tiny enclosure heater

<p align="center">
<a href="assets/hotbox.png"><img src="assets/hotbox.png" alt="HotBox" width="50%" /></a>
</p>

<p align="center"><em>100mm wide, 52mm deep and 177mm high</em></p>

<p align="center">
<a href="assets/Drawing.png"><img src="assets/Drawing.png" alt="HotBox Technical Drawing" width="75%" /></a>
</p>

# 🔥 Disclaimer 🔥

HotBox uses a resistive heating element inside an enclosed space. Built and configured incorrectly, it is a genuine fire risk.

This project is shared as-is for experienced makers who understand the risks. The author accepts no responsibility for damage, injury, or loss of any kind. You build and run this entirely at your own risk.

If you're not comfortable working with high-current DC systems and thermal management, please don't attempt this build.

# BOM

<p align="center">
<a href="assets/BOM.png"><img src="assets/BOM.png" alt="BOM" width="50%" /></a>
</p>

<table>
  <thead>
    <tr>
      <th>#</th>
      <th>Image</th>
      <th>Part</th>
      <th>Description</th>
      <th>Qty</th>
      <th>Notes</th>
      <th>Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td><a href="assets/BOM/PTC-heater.jpg"><img src="assets/BOM/PTC-heater.jpg" alt="PTC Heater" width="80"></a></td>
      <td>PTC Heater Element</td>
      <td>24V 200W ceramic PTC heater</td>
      <td align="center">1</td>
      <td>Self-limiting; derate above 87°C</td>
      <td><a href="https://www.amazon.co.uk/dp/B0DK5W3RKS">amazon.co.uk</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td><a href="assets/BOM/square-thermal-fuse.png"><img src="assets/BOM/square-thermal-fuse.png" alt="Thermal Fuse" width="80"></a></td>
      <td>Square Thermal Fuse</td>
      <td>125°C Ceramic Thermal 250V 15A</td>
      <td align="center">1</td>
      <td>CQC rated; soldered inline</td>
      <td><a href="https://www.amazon.co.uk/dp/B0BNQ7SJYP">amazon.co.uk</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td><a href="assets/BOM/4020-fan.jpg"><img src="assets/BOM/4020-fan.jpg" alt="4020 Fan" width="80"></a></td>
      <td>Axial Fan</td>
      <td>24V 4020 axial fan</td>
      <td align="center">2</td>
      <td>Must run at 100% when element is powered</td>
      <td><a href="https://www.amazon.co.uk/dp/B0FRFMXKSX">amazon.co.uk</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>
        <a href="assets/BOM/NTC-100K-thermistor-OD3mm.jpg">
            <img src="assets/BOM/NTC-100K-thermistor-OD3mm.jpg" alt="NTC 100K thermistor" width="80"/>
        </a>
      </td>
      <td>Thermistor</td>
      <td>NTC 100K</td>
      <td align="center">1</td>
      <td>Seats in dedicated hole in PTC body; use thermal glue</td>
      <td><a href="https://www.amazon.co.uk/dp/B0BDFHZZQX?">amazon.co.uk</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td></td>
      <td>Thermal Glue</td>
      <td>EC360 2W/mK thermal adhesive</td>
      <td align="center">1</td>
      <td>Bonds thermistor to PTC element body</td>
      <td><a href="https://www.amazon.co.uk/dp/B00XQ9AZ8Y">amazon.co.uk</a></td>
    </tr>
    <tr>
      <td>6</td>
      <td><a href="assets/BOM/M3-SHCS-10mm.jpg"><img src="assets/BOM/M3-SHCS-10mm.jpg" alt="M3 SHCS" width="80"></a></td>
      <td>M3×10mm SHCS</td>
      <td>Socket head cap screw</td>
      <td align="center">2</td>
      <td>Secures PTC heater element</td>
      <td></td>
    </tr>
    <tr>
      <td>7</td>
      <td><a href="assets/BOM/M3-SHCS-10mm.jpg"><img src="assets/BOM/M3-SHCS-10mm.jpg" alt="M3 SHCS" width="80"></a></td>
      <td>M3×25mm SHCS</td>
      <td>Socket head cap screw</td>
      <td align="center">2</td>
      <td>Heater case to fan case</td>
      <td></td>
    </tr>
    <tr>
      <td>8</td>
      <td><a href="assets/BOM/M3-SHCS-10mm.jpg"><img src="assets/BOM/M3-SHCS-10mm.jpg" alt="M3 SHCS" width="80"></a></td>
      <td>M3×30mm SHCS</td>
      <td>Socket head cap screw</td>
      <td align="center">4</td>
      <td>Fans through to fan duct</td>
      <td></td>
    </tr>
    <tr>
      <td>9</td>
      <td><a href="assets/BOM/heat-set-inserts.jpg"><img src="assets/BOM/heat-set-inserts.jpg" alt="Heat-Set Insert" width="80"></a></td>
      <td>Heat-Set Insert</td>
      <td>M3×4mm brass heat-set insert</td>
      <td align="center">8</td>
      <td></td>
      <td><a href="https://www.amazon.co.uk/dp/B0DC6RXRB9">amazon.co.uk</a></td>
    </tr>
    <tr>
      <td>10</td>
      <td><a href="assets/BOM/3x3-magnets.jpg"><img src="assets/BOM/3x3-magnets.jpg" alt="3x3mm Magnets" width="80"></a></td>
      <td>Magnets</td>
      <td>3×3mm N42 neodymium magnets</td>
      <td align="center">8</td>
      <td>For lid retention</td>
      <td><a href="https://www.amazon.co.uk/dp/B00389GIK6">amazon.co.uk</a></td>
    </tr>
    <tr>
      <td>11</td>
      <td></td>
      <td>Lid</td>
      <td>Printed part</td>
      <td align="center">1</td>
      <td>Print in ABS/ASA</td>
      <td></td>
    </tr>
    <tr>
      <td>12</td>
      <td></td>
      <td>Heater Case</td>
      <td>Printed part</td>
      <td align="center">1</td>
      <td>Print in ABS/ASA</td>
      <td></td>
    </tr>
    <tr>
      <td>13</td>
      <td></td>
      <td>Fan Case</td>
      <td>Printed part</td>
      <td align="center">1</td>
      <td>Print in ABS/ASA</td>
      <td></td>
    </tr>
    <tr>
      <td>14</td>
      <td></td>
      <td>Fan Duct</td>
      <td>Printed part</td>
      <td align="center">1</td>
      <td>Print in ABS/ASA</td>
      <td></td>
    </tr>
    <tr>
      <td>15</td>
      <td></td>
      <td>Fan Duct ZeroG Nebula</td>
      <td>Printed part</td>
      <td align="center">1</td>
      <td>Print in ABS/ASA; alternative duct for ZeroG Nebula enclosure</td>
      <td></td>
    </tr>
  </tbody>
</table>

# ZeroG Nebula

<p align="center">
<a href="assets/ZeroG-Nebula.png"><img src="assets/ZeroG-Nebula.png" alt="ZeroG-Nebula" width="50%" /></a>
</p>

# Gotchas

- PID calibration may not work close to the enclosure's thermal limit. If the enclosure cannot reliably reach and re-reach the target temperature through multiple oscillation cycles, the calibration will fail. Try a lower target temperature (e.g. TARGET=50 instead of TARGET=60).

- PTC heater elements are self-limiting — they reduce power output as they approach their rated temperature. This makes PID calibration difficult as the element may throttle itself during the calibration oscillation cycles.

- Do NOT run PID_CALIBRATE with the fans configured as [fan_generic] controlled via delayed_gcode macros. Klipper holds the gcode queue during PID_CALIBRATE, which prevents delayed_gcode from executing, meaning fans will not run. This WILL cause the element to overheat. The fans MUST be configured as [temperature_fan] so they operate independently of the gcode queue.

- The hotbox fans must run at 100% whenever the PTC element is receiving power. This is not optional — the element will overheat and blow the thermal fuse without active cooling.

- Always let the fans cool the elemet down to 50 degrees or below before switching the machine off.
- There is a big thermal delay between the PTC element and the thermistor due to the distance between the two. Use thermal glue to bridge the gap, but factor this delay into any calculations
- Running the PTC heater above 87°C for extended periods risks triggering the 125°C thermal fuse. The HOTBOX_CONTROL overtemp cutoff should be set to 87°C maximum.

- The thermistor must be seated directly in the dedicated hole in the PTC element body. Poor contact will cause it to read significantly below actual element temperature, meaning the emergency stop and overtemp cutoff will not trigger in time to protect the thermal fuse.

- The [temperature_fan] target is user-editable in Mainsail/Fluidd. Setting it above the element's safe operating temperature will prevent fans from running at the correct threshold. Do not modify this value.

- Klipper's max_temp on the [temperature_fan] section is an emergency shutdown threshold, not a cap on the settable target. Setting it too low will cause Klipper to hard-stop during normal operation.

- There needs to be enough overhead in the PSU to power a 200W PTC heater on the 24v rail, do the maths and ensure that there's enough power. If not, run an additional 200W DIN rail PSU or upgrade

- Do NOT use `control: watermark` for the chamber heater. Bang-bang switching of the heating element causes hard current transients on the shared 24V rail which affect TMC stepper driver behaviour, producing Z-axis banding artefacts on prints. Always use `control: pid` with `pwm_cycle_time: 0.01` to smooth current draw to a near-constant average.
