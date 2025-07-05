@(LoadCompany "")
<section>
@(DieseFirma.intro)


### Firmenangaben

<table>
	<tr>
		<td width="150" align="right">Firma:</td>
		<td>@(DieseFirma.name1)</td>
	</tr>
	<tr>
		<td width="150" align="right">Anschrift:</td>
		<td>@(DieseFirma.strasse)<br />
		   @(DieseFirma.plz) @(DieseFirma.ort)</td>
	</tr>
	<tr>
		<td width="150" align="right">Bankverbindungen:</td>
		<td>@(DieseFirma.bank1name)<br />
                    @(DieseFirma.bank1iban)<br />
		    @(DieseFirma.bank1bic)<br /><br />
                    @(DieseFirma.bank2name)<br />
		    @(DieseFirma.bank2iban)<br />
		    @(DieseFirma.bank2bic)</td>
	</tr>
	<tr>
		<td width="150" align="right">USt-IdNr.:</td>
                <td>@(DieseFirma.ustid)</td>
	</tr>
	<tr>
		<td width="150" align="right">Kontenrahmen:</td>
		<td>@(DieseFirma.kontenrahmen)</td>
	</tr>
	<tr>
		<td width="150" align="right">Wirtschaftsjahr:</td>
		<td>@(DieseFirma.wirtschaftsjahr), @(DieseFirma.buchungsperioden) Buchungsperioden</td>
	</tr>
	<tr>
		<td width="150" align="right">Gewinnermittlungsart:</td>
		<td>@(DieseFirma.gewinnermittlung)</td>
	</tr>
	<tr>
		<td width="150" align="right">Art der Besteuerung:</td>
		<td>@(DieseFirma.ustbesteuerung)</td>
	</tr>
	<tr>
		<td width="150" align="right">Buchungsjahr:</td>
		<td>@(DieseFirma.jahr)</td>
	</tr>
</table>

</section>
