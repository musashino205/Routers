# othar devices
現在所有している機種（ar71xx/ath79, ramipsを除く）の一覧

## Wireless Router

<table>
	<thead>
		<tr class="active">
			<th>Manuf.</th>
			<th>Model</th>
			<th>SoC</th>
			<th>OpenWrt Support</th>
			<th>target</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>ASUS</td>
			<td><s>Lyra mini (MAP-AC1300)</s> 故障</td>
			<td>IPQ4018</td>
			<td>stop</td>
			<td>ipq40xx</td>
		</tr>
		<tr>
			<td rowspan="5">BUFFALO</td>
			<td>WZR-900DHP</td>
			<td>BCM47081A0</td>
			<td>&#9675;</td>
			<td>bcm53xx</td>
		</tr>
		<tr>
			<td>WSR-2533DHP2</td>
			<td>MT7622B</td>
			<td>&#9675;</td>
			<td>mediatek</td>
		</tr>
		<tr>
			<td>WSR-3200AX4S</td>
			<td>MT7622B</td>
			<td>WIP</td>
			<td>mediatek</td>
		</tr>
		<tr>
			<td>WXR-2533DHP</td>
			<td>IPQ8064</td>
			<td>&#9675;</td>
			<td>ipq806x</td>
		</tr>
		<tr>
			<td>WXR-5950AX12</td>
			<td>IPQ8078</td>
			<td>WIP</td>
			<td>ipq807x</td>
		</tr>
		<tr>
			<td rowspan="1">ELECOM</td>
			<td>WRC-X3200GST3</td>
			<td>MT7622B</td>
			<td>WIP</td>
			<td>mediatek</td>
		</tr>
		<tr>
			<td rowspan="2">NEC</td>
			<td>WG2600HP</td>
			<td>IPQ8064</td>
			<td>&#9675;</td>
			<td>ipq806x</td>
		</tr>
		<tr>
			<td>WG2600HP2</td>
			<td>IPQ8064</td>
			<td>&#9675; (WG2600HP)<a href="https://github.com/musashino205/routers/issues/1#issuecomment-764398696" target="blank">*</a></td>
			<td>ipq806x</td>
		</tr>
		<tr>
			<td rowspan="1">NETGEAR</td>
			<td>R7800</td>
			<td>IPQ8065</td>
			<td>&#9675;</td>
			<td>ipq806x</td>
		</tr>
		<tr>
			<td>SONY</td>
			<td>NCP-HG100</td>
			<td>IPQ4019</td>
			<td>WIP</td>
			<td>ipq40xx</td>
		</tr>
	</tbody>
</table>
<br>

## Switching Hub

<table>
	<thead>
		<tr class="active">
			<th>Manuf.</th>
			<th>Model</th>
			<th>SoC</th>
			<th>OpenWrt Support</th>
			<th>target</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td rowspan="1">INABA</td>
			<td>Abaniact AML2-17GP</td>
			<td>RTL8382M</td>
			<td>WIP</td>
			<td>realtek</td>
		</tr>
		<tr>
			<td rowspan="1">I-O DATA</td>
			<td>BSH-G24MB</td>
			<td>RTL8382M</td>
			<td>WIP</td>
			<td>realtek</td>
		</tr>
		<tr>
			<td rowspan="1">Panasonic</td>
			<td>Switch-M24eG PN28240K</td>
			<td>RTL8382M</td>
			<td>Planning</td>
			<td>realtek</td>
		</tr>
	</tbody>
</table>
<br>

## Unsupportable Devices

<table>
	<thead>
		<tr class="active">
			<th>Manuf.</th>
			<th>Model</th>
			<th>SoC</th>
			<th>OpenWrt Support</th>
			<th>target</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>BUFFALO</td>
			<td>WSR-1166DHP3</td>
			<td>RTL8197F</td>
			<td>&#10005;</td>
			<td>None</td>
		</tr>
		<tr>
			<td>I-O DATA</td>
			<td>WN-G300GR</td>
			<td>RTL8198</td>
			<td>&#10005;</td>
			<td>None</td>
		</tr>
	</tbody>
</table>
