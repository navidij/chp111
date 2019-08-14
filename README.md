# CHP 111 
CHP 111 - Chem Eqx Bal 
Created (beta) for Prof C. Li Summ 2019 HCCC

<form action="#" method="get" onsubmit="doBalance(); return false;">
	<table class="noborder">
		<tbody>
			<tr>
				<td style="width:4%"><label for="inputFormula">Unbal. Eqx:</label></td>
				<td style="width:96%; display:flex; flex-direction:row">
					<input type="text" id="inputFormula" autocomplete="off" placeholder="Enter the unbalanced chemical equation here" style="flex-grow:1; font-family:serif"/>
					<input type="submit" value="Balance" style="margin-left:0.3em"/>
				</td>
			</tr>
			<tr style="height:3em">
				<td style="vertical-align:middle">Bal. Eqx:</td>
				<td><span id="balanced" style="font-family:serif; font-size:150%; line-height:1.6;"></span><span id="message"></span></td>
			</tr>
			<tr>
				<td></td>
				<td><code id="codeOutput">&#xA0;</code></td>
			</tr>
		</tbody>
	</table>
</form>
<script type="application/javascript" src="/chp111/ceb.js"></script>
