<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns:m="http://schemas.microsoft.com/office/2004/12/omml"
xmlns:st1="urn:schemas-microsoft-com:office:smarttags"
xmlns="http://www.w3.org/TR/REC-html40">

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 15">
<meta name=Originator content="Microsoft Word 15">
<link rel=File-List href="e_files/filelist.xml">
<title>Linux Server Configuration</title>
<o:SmartTagType namespaceuri="urn:schemas-microsoft-com:office:smarttags"
 name="PlaceName"/>
<o:SmartTagType namespaceuri="urn:schemas-microsoft-com:office:smarttags"
 name="PlaceType"/>
<o:SmartTagType namespaceuri="urn:schemas-microsoft-com:office:smarttags"
 name="date"/>
<o:SmartTagType namespaceuri="urn:schemas-microsoft-com:office:smarttags"
 name="time"/>
<o:SmartTagType namespaceuri="urn:schemas-microsoft-com:office:smarttags"
 name="State"/>
<o:SmartTagType namespaceuri="urn:schemas-microsoft-com:office:smarttags"
 name="place"/>
<!--[if gte mso 9]><xml>
 <o:DocumentProperties>
  <o:Author>Sukarna Barua &amp; Iqbal Hossain</o:Author>
  <o:LastAuthor>Rodrigo da Costa Sobrinho</o:LastAuthor>
  <o:Revision>2</o:Revision>
  <o:TotalTime>2</o:TotalTime>
  <o:LastPrinted>2009-09-30T13:50:00Z</o:LastPrinted>
  <o:Created>2023-07-08T16:05:00Z</o:Created>
  <o:LastSaved>2023-07-08T16:05:00Z</o:LastSaved>
  <o:Pages>72</o:Pages>
  <o:Words>19805</o:Words>
  <o:Characters>106951</o:Characters>
  <o:Company>shahidsmritihall</o:Company>
  <o:Lines>891</o:Lines>
  <o:Paragraphs>253</o:Paragraphs>
  <o:CharactersWithSpaces>126503</o:CharactersWithSpaces>
  <o:Version>16.00</o:Version>
 </o:DocumentProperties>
 <o:OfficeDocumentSettings>
  <o:TargetScreenSize>800x600</o:TargetScreenSize>
 </o:OfficeDocumentSettings>
</xml><![endif]-->
<link rel=themeData href="e_files/themedata.thmx">
<link rel=colorSchemeMapping href="e_files/colorschememapping.xml">
<!--[if gte mso 9]><xml>
 <w:WordDocument>
  <w:TrackMoves>false</w:TrackMoves>
  <w:TrackFormatting/>
  <w:ValidateAgainstSchemas/>
  <w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
  <w:IgnoreMixedContent>false</w:IgnoreMixedContent>
  <w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
  <w:DoNotPromoteQF/>
  <w:LidThemeOther>PT-BR</w:LidThemeOther>
  <w:LidThemeAsian>X-NONE</w:LidThemeAsian>
  <w:LidThemeComplexScript>X-NONE</w:LidThemeComplexScript>
  <w:Compatibility>
   <w:BreakWrappedTables/>
   <w:SnapToGridInCell/>
   <w:WrapTextWithPunct/>
   <w:UseAsianBreakRules/>
   <w:UseWord2002TableStyleRules/>
   <w:UseWord2010TableStyleRules/>
   <w:DontUseIndentAsNumberingTabStop/>
   <w:FELineBreak11/>
   <w:WW11IndentRules/>
   <w:DontAutofitConstrainedTables/>
   <w:AutofitLikeWW11/>
   <w:HangulWidthLikeWW11/>
   <w:UseNormalStyleForList/>
   <w:DontVertAlignCellWithSp/>
   <w:DontBreakConstrainedForcedTables/>
   <w:DontVertAlignInTxbx/>
   <w:Word11KerningPairs/>
   <w:CachedColBalance/>
  </w:Compatibility>
  <w:BrowserLevel>MicrosoftInternetExplorer4</w:BrowserLevel>
  <m:mathPr>
   <m:mathFont m:val="Cambria Math"/>
   <m:brkBin m:val="before"/>
   <m:brkBinSub m:val="&#45;-"/>
   <m:smallFrac m:val="off"/>
   <m:dispDef/>
   <m:lMargin m:val="0"/>
   <m:rMargin m:val="0"/>
   <m:defJc m:val="centerGroup"/>
   <m:wrapIndent m:val="1440"/>
   <m:intLim m:val="subSup"/>
   <m:naryLim m:val="undOvr"/>
  </m:mathPr></w:WordDocument>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <w:LatentStyles DefLockedState="false" DefUnhideWhenUsed="false"
  DefSemiHidden="false" DefQFormat="false" DefPriority="99"
  LatentStyleCount="376">
  <w:LsdException Locked="false" Priority="0" QFormat="true" Name="Normal"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 1"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 2"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 3"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 4"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 5"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 6"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 7"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 8"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 9"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 1"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 2"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 3"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 4"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 5"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 6"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 7"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 8"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="header"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footer"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index heading"/>
  <w:LsdException Locked="false" Priority="35" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="caption"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of figures"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope return"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="line number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="page number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of authorities"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="macro"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="toa heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 5"/>
  <w:LsdException Locked="false" Priority="10" QFormat="true" Name="Title"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Closing"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Signature"/>
  <w:LsdException Locked="false" Priority="0" SemiHidden="true"
   UnhideWhenUsed="true" Name="Default Paragraph Font"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Message Header"/>
  <w:LsdException Locked="false" Priority="11" QFormat="true" Name="Subtitle"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Salutation"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Date"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Note Heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Block Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Hyperlink"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="FollowedHyperlink"/>
  <w:LsdException Locked="false" Priority="22" QFormat="true" Name="Strong"/>
  <w:LsdException Locked="false" Priority="20" QFormat="true" Name="Emphasis"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Document Map"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Plain Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="E-mail Signature"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Top of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Bottom of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal (Web)"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Acronym"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Cite"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Code"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Definition"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Keyboard"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Preformatted"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Sample"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Typewriter"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Variable"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Table"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation subject"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="No List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Contemporary"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Elegant"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Professional"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Balloon Text"/>
  <w:LsdException Locked="false" Priority="39" Name="Table Grid"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Theme"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Placeholder Text"/>
  <w:LsdException Locked="false" Priority="1" QFormat="true" Name="No Spacing"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 1"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 1"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Revision"/>
  <w:LsdException Locked="false" Priority="34" QFormat="true"
   Name="List Paragraph"/>
  <w:LsdException Locked="false" Priority="29" QFormat="true" Name="Quote"/>
  <w:LsdException Locked="false" Priority="30" QFormat="true"
   Name="Intense Quote"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 1"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 1"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 2"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 2"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 2"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 3"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 3"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 3"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 4"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 4"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 4"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 5"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 5"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 5"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 6"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 6"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 6"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="19" QFormat="true"
   Name="Subtle Emphasis"/>
  <w:LsdException Locked="false" Priority="21" QFormat="true"
   Name="Intense Emphasis"/>
  <w:LsdException Locked="false" Priority="31" QFormat="true"
   Name="Subtle Reference"/>
  <w:LsdException Locked="false" Priority="32" QFormat="true"
   Name="Intense Reference"/>
  <w:LsdException Locked="false" Priority="33" QFormat="true" Name="Book Title"/>
  <w:LsdException Locked="false" Priority="37" SemiHidden="true"
   UnhideWhenUsed="true" Name="Bibliography"/>
  <w:LsdException Locked="false" Priority="39" QFormat="true" Name="TOC Heading"/>
  <w:LsdException Locked="false" Priority="41" Name="Plain Table 1"/>
  <w:LsdException Locked="false" Priority="42" Name="Plain Table 2"/>
  <w:LsdException Locked="false" Priority="43" Name="Plain Table 3"/>
  <w:LsdException Locked="false" Priority="44" Name="Plain Table 4"/>
  <w:LsdException Locked="false" Priority="45" Name="Plain Table 5"/>
  <w:LsdException Locked="false" Priority="40" Name="Grid Table Light"/>
  <w:LsdException Locked="false" Priority="46" Name="Grid Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="Grid Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="Grid Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="46" Name="List Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="List Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="List Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Mention"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Smart Hyperlink"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Hashtag"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Unresolved Mention"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Smart Link"/>
 </w:LatentStyles>
</xml><![endif]--><!--[if !mso]><object
 classid="clsid:38481807-CA0E-42D2-BF39-B33AF135CC4D" id=ieooui></object>
<style>
st1\:*{behavior:url(#ieooui) }
</style>
<![endif]-->
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Helvetica;
	panose-1:2 11 6 4 2 2 2 2 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:Courier;
	panose-1:2 7 4 9 2 2 5 2 4 4;
	mso-font-charset:0;
	mso-generic-font-family:modern;
	mso-font-format:other;
	mso-font-pitch:fixed;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:"Tms Rmn";
	panose-1:2 2 6 3 4 5 5 2 3 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-format:other;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:Helv;
	panose-1:2 11 6 4 2 2 2 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-format:other;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:"New York";
	panose-1:2 4 5 3 6 5 6 2 3 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:System;
	panose-1:0 0 0 0 0 0 0 0 0 0;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-format:other;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:Wingdings;
	panose-1:5 0 0 0 0 0 0 0 0 0;
	mso-font-charset:2;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:0 268435456 0 0 -2147483648 0;}
@font-face
	{font-family:"MS Mincho";
	panose-1:2 2 6 9 4 2 5 8 3 4;
	mso-font-alt:"\FF2D\FF33 \660E\671D";
	mso-font-charset:128;
	mso-generic-font-family:roman;
	mso-font-pitch:fixed;
	mso-font-signature:1 134676480 16 0 131072 0;}
@font-face
	{font-family:Batang;
	panose-1:2 3 6 0 0 1 1 1 1 1;
	mso-font-alt:\BC14\D0D5;
	mso-font-charset:129;
	mso-generic-font-family:auto;
	mso-font-pitch:fixed;
	mso-font-signature:1 151388160 16 0 524288 0;}
@font-face
	{font-family:SimSun;
	panose-1:2 1 6 0 3 1 1 1 1 1;
	mso-font-alt:\5B8B\4F53;
	mso-font-charset:134;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:1 135135232 16 0 262144 0;}
@font-face
	{font-family:PMingLiU;
	panose-1:2 1 6 1 0 1 1 1 1 1;
	mso-font-alt:\65B0\7D30\660E\9AD4;
	mso-font-charset:136;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:1 134742016 16 0 1048576 0;}
@font-face
	{font-family:"MS Gothic";
	panose-1:2 11 6 9 7 2 5 8 2 4;
	mso-font-alt:"\FF2D\FF33 \30B4\30B7\30C3\30AF";
	mso-font-charset:128;
	mso-generic-font-family:modern;
	mso-font-pitch:fixed;
	mso-font-signature:1 134676480 16 0 131072 0;}
@font-face
	{font-family:Dotum;
	panose-1:2 11 6 0 0 1 1 1 1 1;
	mso-font-alt:\B3CB\C6C0;
	mso-font-charset:129;
	mso-generic-font-family:modern;
	mso-font-pitch:fixed;
	mso-font-signature:1 151388160 16 0 524288 0;}
@font-face
	{font-family:SimHei;
	panose-1:2 1 6 0 3 1 1 1 1 1;
	mso-font-alt:\9ED1\4F53;
	mso-font-charset:134;
	mso-generic-font-family:modern;
	mso-font-pitch:fixed;
	mso-font-signature:1 135135232 16 0 262144 0;}
@font-face
	{font-family:MingLiU;
	panose-1:2 1 6 9 0 1 1 1 1 1;
	mso-font-alt:\7D30\660E\9AD4;
	mso-font-charset:136;
	mso-generic-font-family:modern;
	mso-font-pitch:fixed;
	mso-font-signature:1 134742016 16 0 1048576 0;}
@font-face
	{font-family:Mincho;
	panose-1:2 2 6 9 4 3 5 8 3 5;
	mso-font-alt:\660E\671D;
	mso-font-charset:128;
	mso-generic-font-family:roman;
	mso-font-pitch:fixed;
	mso-font-signature:1 134676480 16 0 131072 0;}
@font-face
	{font-family:Gulim;
	panose-1:2 11 6 0 0 1 1 1 1 1;
	mso-font-alt:\AD74\B9BC;
	mso-font-charset:129;
	mso-generic-font-family:roman;
	mso-font-pitch:fixed;
	mso-font-signature:1 151388160 16 0 524288 0;}
@font-face
	{font-family:Century;
	panose-1:2 4 6 4 5 5 5 2 3 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:"Angsana New";
	panose-1:2 2 6 3 5 4 5 2 3 4;
	mso-font-charset:222;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:16777217 0 0 0 65536 0;}
@font-face
	{font-family:"Cordia New";
	panose-1:2 11 3 4 2 2 2 2 2 4;
	mso-font-charset:222;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:16777217 0 0 0 65536 0;}
@font-face
	{font-family:Mangal;
	panose-1:0 0 4 0 0 0 0 0 0 0;
	mso-font-charset:1;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:8192 0 0 0 0 0;}
@font-face
	{font-family:Latha;
	panose-1:2 0 4 0 0 0 0 0 0 0;
	mso-font-charset:1;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:262144 0 0 0 0 0;}
@font-face
	{font-family:Sylfaen;
	panose-1:1 10 5 2 5 3 6 3 3 3;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:67110535 0 0 0 159 0;}
@font-face
	{font-family:Vrinda;
	panose-1:0 0 4 0 0 0 0 0 0 0;
	mso-font-charset:1;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:0 0 0 0 0 0;}
@font-face
	{font-family:Raavi;
	panose-1:2 0 5 0 0 0 0 0 0 0;
	mso-font-charset:1;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:0 0 0 0 0 0;}
@font-face
	{font-family:Shruti;
	panose-1:2 0 5 0 0 0 0 0 0 0;
	mso-font-charset:1;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:0 0 0 0 0 0;}
@font-face
	{font-family:Sendnya;
	panose-1:0 0 4 0 0 0 0 0 0 0;
	mso-font-charset:1;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:0 0 0 0 0 0;}
@font-face
	{font-family:Gautami;
	panose-1:2 0 5 0 0 0 0 0 0 0;
	mso-font-charset:1;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:0 0 0 0 0 0;}
@font-face
	{font-family:Tunga;
	panose-1:0 0 4 0 0 0 0 0 0 0;
	mso-font-charset:1;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:0 0 0 0 0 0;}
@font-face
	{font-family:"Estrangelo Edessa";
	panose-1:0 0 0 0 0 0 0 0 0 0;
	mso-font-charset:1;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:0 0 0 0 0 0;}
@font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-536869121 1107305727 33554432 0 415 0;}
@font-face
	{font-family:"Yu Gothic";
	panose-1:2 11 4 0 0 0 0 0 0 0;
	mso-font-alt:\6E38\30B4\30B7\30C3\30AF;
	mso-font-charset:128;
	mso-generic-font-family:modern;
	mso-font-pitch:fixed;
	mso-font-signature:1 134676480 16 0 131072 0;}
@font-face
	{font-family:DengXian;
	panose-1:2 1 6 0 3 1 1 1 1 1;
	mso-font-alt:\7B49\7EBF;
	mso-font-charset:134;
	mso-generic-font-family:modern;
	mso-font-pitch:fixed;
	mso-font-signature:1 135135232 16 0 262144 0;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1073732485 9 0 511 0;}
@font-face
	{font-family:"Calibri Light";
	panose-1:2 15 3 2 2 2 4 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1073732485 9 0 511 0;}
@font-face
	{font-family:"Palatino Linotype";
	panose-1:2 4 5 2 5 5 5 3 3 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:Verdana;
	panose-1:2 11 6 4 3 5 4 4 2 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:"Arial Unicode MS";
	panose-1:2 11 6 4 2 2 2 2 2 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:"Segoe UI Emoji";
	panose-1:2 11 5 2 4 2 4 2 2 3;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:auto;
	mso-font-signature:0 0 0 0 0 0;}
@font-face
	{font-family:Cambria;
	panose-1:2 4 5 3 5 4 6 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-536869121 1107305727 33554432 0 415 0;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-parent:"";
	margin:0cm;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
h1
	{mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Heading 1 Char";
	mso-style-next:Normal;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	page-break-after:avoid;
	mso-outline-level:1;
	font-size:16.0pt;
	font-family:"Cambria",serif;
	mso-font-kerning:16.0pt;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	font-weight:bold;}
h2
	{mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Heading 2 Char";
	mso-style-next:Normal;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	page-break-after:avoid;
	mso-outline-level:2;
	font-size:14.0pt;
	font-family:"Arial",sans-serif;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	font-weight:bold;
	font-style:italic;}
h3
	{mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Heading 3 Char";
	mso-style-next:Normal;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	text-indent:0cm;
	mso-pagination:widow-orphan;
	page-break-after:avoid;
	mso-outline-level:3;
	mso-list:l35 level3 lfo33;
	font-size:13.0pt;
	font-family:"Arial",sans-serif;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	font-weight:bold;}
h4
	{mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Heading 4 Char";
	mso-style-next:Normal;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	text-indent:0cm;
	mso-pagination:widow-orphan;
	page-break-after:avoid;
	mso-outline-level:4;
	mso-list:l35 level4 lfo33;
	font-size:14.0pt;
	font-family:"Times New Roman",serif;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	font-weight:bold;}
h5
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-next:Normal;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	text-indent:0cm;
	mso-pagination:widow-orphan;
	mso-outline-level:5;
	mso-list:l35 level5 lfo33;
	font-size:13.0pt;
	font-family:"Times New Roman",serif;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	font-weight:bold;
	font-style:italic;}
h6
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-next:Normal;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	text-indent:0cm;
	mso-pagination:widow-orphan;
	mso-outline-level:6;
	mso-list:l35 level6 lfo33;
	font-size:11.0pt;
	font-family:"Times New Roman",serif;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	font-weight:bold;}
p.MsoHeading7, li.MsoHeading7, div.MsoHeading7
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-next:Normal;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	text-indent:0cm;
	mso-pagination:widow-orphan;
	mso-outline-level:7;
	mso-list:l35 level7 lfo33;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoHeading8, li.MsoHeading8, div.MsoHeading8
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-next:Normal;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	text-indent:0cm;
	mso-pagination:widow-orphan;
	mso-outline-level:8;
	mso-list:l35 level8 lfo33;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	font-style:italic;}
p.MsoHeading9, li.MsoHeading9, div.MsoHeading9
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-next:Normal;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	text-indent:0cm;
	mso-pagination:widow-orphan;
	mso-outline-level:9;
	mso-list:l35 level9 lfo33;
	font-size:11.0pt;
	font-family:"Arial",sans-serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoIndex1, li.MsoIndex1, div.MsoIndex1
	{mso-style-update:auto;
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-next:Normal;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:12.0pt;
	text-indent:-12.0pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoToc1, li.MsoToc1, div.MsoToc1
	{mso-style-update:auto;
	mso-style-priority:39;
	mso-style-next:Normal;
	margin:0cm;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoToc2, li.MsoToc2, div.MsoToc2
	{mso-style-update:auto;
	mso-style-priority:39;
	mso-style-next:Normal;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:12.0pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoToc3, li.MsoToc3, div.MsoToc3
	{mso-style-update:auto;
	mso-style-priority:39;
	mso-style-next:Normal;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:24.0pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoToc4, li.MsoToc4, div.MsoToc4
	{mso-style-update:auto;
	mso-style-priority:39;
	mso-style-next:Normal;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:5.0pt;
	margin-left:33.0pt;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoToc5, li.MsoToc5, div.MsoToc5
	{mso-style-update:auto;
	mso-style-priority:39;
	mso-style-next:Normal;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:5.0pt;
	margin-left:44.0pt;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoToc6, li.MsoToc6, div.MsoToc6
	{mso-style-update:auto;
	mso-style-priority:39;
	mso-style-next:Normal;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:5.0pt;
	margin-left:55.0pt;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoToc7, li.MsoToc7, div.MsoToc7
	{mso-style-update:auto;
	mso-style-priority:39;
	mso-style-next:Normal;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:5.0pt;
	margin-left:66.0pt;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoToc8, li.MsoToc8, div.MsoToc8
	{mso-style-update:auto;
	mso-style-priority:39;
	mso-style-next:Normal;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:5.0pt;
	margin-left:77.0pt;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoToc9, li.MsoToc9, div.MsoToc9
	{mso-style-update:auto;
	mso-style-priority:39;
	mso-style-next:Normal;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:5.0pt;
	margin-left:88.0pt;
	line-height:115%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoHeader, li.MsoHeader, div.MsoHeader
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-link:"Header Char";
	margin:0cm;
	mso-pagination:widow-orphan;
	tab-stops:center 234.0pt right 468.0pt;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoFooter, li.MsoFooter, div.MsoFooter
	{mso-style-priority:99;
	mso-style-link:"Footer Char";
	margin:0cm;
	mso-pagination:widow-orphan;
	tab-stops:center 234.0pt right 468.0pt;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
a:link, span.MsoHyperlink
	{mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-parent:"";
	color:blue;
	text-decoration:underline;
	text-underline:single;}
a:visited, span.MsoHyperlinkFollowed
	{mso-style-noshow:yes;
	mso-style-priority:99;
	color:#954F72;
	mso-themecolor:followedhyperlink;
	text-decoration:underline;
	text-underline:single;}
p
	{mso-style-priority:99;
	mso-style-unhide:no;
	mso-margin-top-alt:auto;
	margin-right:0cm;
	mso-margin-bottom-alt:auto;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
code
	{mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-parent:"";
	font-family:"Courier New";
	mso-ascii-font-family:"Courier New";
	mso-fareast-font-family:"Times New Roman";
	mso-hansi-font-family:"Courier New";
	mso-bidi-font-family:"Courier New";}
kbd
	{mso-style-unhide:no;
	mso-style-parent:"";
	font-family:"Courier New";
	mso-ascii-font-family:"Courier New";
	mso-fareast-font-family:"Times New Roman";
	mso-hansi-font-family:"Courier New";
	mso-bidi-font-family:"Courier New";}
pre
	{mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-link:"HTML Preformatted Char";
	margin:0cm;
	mso-pagination:widow-orphan;
	tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt;
	font-size:10.0pt;
	font-family:"Courier New";
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
tt
	{mso-style-unhide:no;
	mso-style-parent:"";
	font-family:"Courier New";
	mso-ascii-font-family:"Courier New";
	mso-fareast-font-family:"Times New Roman";
	mso-hansi-font-family:"Courier New";
	mso-bidi-font-family:"Courier New";}
p.MsoTocHeading, li.MsoTocHeading, div.MsoTocHeading
	{mso-style-priority:39;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-parent:"Heading 1";
	mso-style-next:Normal;
	margin-top:24.0pt;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:0cm;
	line-height:115%;
	mso-pagination:widow-orphan lines-together;
	page-break-after:avoid;
	font-size:14.0pt;
	font-family:"Cambria",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	color:#365F91;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	font-weight:bold;}
p.para, li.para, div.para
	{mso-style-name:para;
	mso-style-unhide:no;
	mso-margin-top-alt:auto;
	margin-right:0cm;
	mso-margin-bottom-alt:auto;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
span.quote
	{mso-style-name:quote;
	mso-style-unhide:no;}
span.Heading1Char
	{mso-style-name:"Heading 1 Char";
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-parent:"";
	mso-style-link:"Heading 1";
	mso-ansi-font-size:16.0pt;
	mso-bidi-font-size:16.0pt;
	font-family:"Cambria",serif;
	mso-ascii-font-family:Cambria;
	mso-hansi-font-family:Cambria;
	mso-font-kerning:16.0pt;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	mso-bidi-language:AR-SA;
	font-weight:bold;}
span.il
	{mso-style-name:il;
	mso-style-unhide:no;}
span.Heading2Char
	{mso-style-name:"Heading 2 Char";
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-parent:"";
	mso-style-link:"Heading 2";
	mso-ansi-font-size:14.0pt;
	mso-bidi-font-size:14.0pt;
	font-family:"Arial",sans-serif;
	mso-ascii-font-family:Arial;
	mso-hansi-font-family:Arial;
	mso-bidi-font-family:Arial;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	mso-bidi-language:AR-SA;
	font-weight:bold;
	font-style:italic;}
span.Heading3Char
	{mso-style-name:"Heading 3 Char";
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-parent:"";
	mso-style-link:"Heading 3";
	mso-ansi-font-size:13.0pt;
	mso-bidi-font-size:13.0pt;
	font-family:"Arial",sans-serif;
	mso-ascii-font-family:Arial;
	mso-hansi-font-family:Arial;
	mso-bidi-font-family:Arial;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	mso-bidi-language:AR-SA;
	font-weight:bold;}
span.HTMLPreformattedChar
	{mso-style-name:"HTML Preformatted Char";
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-parent:"";
	mso-style-link:"HTML Preformatted";
	font-family:"Courier New";
	mso-ascii-font-family:"Courier New";
	mso-hansi-font-family:"Courier New";
	mso-bidi-font-family:"Courier New";}
span.Heading4Char
	{mso-style-name:"Heading 4 Char";
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-parent:"";
	mso-style-link:"Heading 4";
	mso-ansi-font-size:14.0pt;
	mso-bidi-font-size:14.0pt;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	mso-bidi-language:AR-SA;
	font-weight:bold;}
span.italic
	{mso-style-name:italic;
	mso-style-unhide:no;}
span.term
	{mso-style-name:term;
	mso-style-unhide:no;}
span.HeaderChar
	{mso-style-name:"Header Char";
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-parent:"";
	mso-style-link:Header;
	mso-ansi-font-size:12.0pt;
	mso-bidi-font-size:12.0pt;}
span.FooterChar
	{mso-style-name:"Footer Char";
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-parent:"";
	mso-style-link:Footer;
	mso-ansi-font-size:12.0pt;
	mso-bidi-font-size:12.0pt;}
p.TimesNewRoman, li.TimesNewRoman, div.TimesNewRoman
	{mso-style-name:"Times New Roman";
	mso-style-unhide:no;
	mso-style-link:"Times New Roman Char";
	margin:0cm;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
span.TimesNewRomanChar
	{mso-style-name:"Times New Roman Char";
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-parent:"";
	mso-style-link:"Times New Roman";
	mso-ansi-font-size:11.0pt;
	mso-bidi-font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-hansi-font-family:Calibri;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	mso-bidi-language:AR-SA;}
span.msoIns
	{mso-style-type:export-only;
	mso-style-name:"";
	text-decoration:underline;
	text-underline:single;
	color:teal;}
span.msoDel
	{mso-style-type:export-only;
	mso-style-name:"";
	text-decoration:line-through;
	color:red;}
.MsoChpDefault
	{mso-style-type:export-only;
	mso-default-props:yes;}
 /* Page Definitions */
 @page
	{mso-footnote-separator:url("e_files/header.htm") fs;
	mso-footnote-continuation-separator:url("e_files/header.htm") fcs;
	mso-endnote-separator:url("e_files/header.htm") es;
	mso-endnote-continuation-separator:url("e_files/header.htm") ecs;}
@page WordSection1
	{size:612.0pt 792.0pt;
	margin:72.0pt 90.0pt 72.0pt 90.0pt;
	mso-header-margin:36.0pt;
	mso-footer-margin:36.0pt;
	mso-footer:url("e_files/header.htm") f1;
	mso-paper-source:0;}
div.WordSection1
	{page:WordSection1;}
@page WordSection2
	{size:612.0pt 792.0pt;
	margin:72.0pt 90.0pt 72.0pt 90.0pt;
	mso-header-margin:36.0pt;
	mso-footer-margin:36.0pt;
	mso-footer:url("e_files/header.htm") f1;
	mso-paper-source:0;}
div.WordSection2
	{page:WordSection2;}
 /* List Definitions */
 @list l0
	{mso-list-id:12341177;
	mso-list-template-ids:-1988214420;}
@list l0:level1
	{mso-level-suffix:space;
	mso-level-text:"Chapter %1";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l0:level2
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l0:level3
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l0:level4
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l0:level5
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l0:level6
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l0:level7
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l0:level8
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l0:level9
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l1
	{mso-list-id:63308556;
	mso-list-type:hybrid;
	mso-list-template-ids:159446274 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l1:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l1:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l1:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l1:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l1:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l1:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l1:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l1:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l1:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l2
	{mso-list-id:95297798;
	mso-list-template-ids:659748686;}
@list l2:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l2:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l2:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l2:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l2:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l2:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l2:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l2:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l2:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l3
	{mso-list-id:102380001;
	mso-list-template-ids:1315857002;
	mso-list-style-name:"Style Style Style Outline numbered Arial 13 pt Bold + Outline numbe\.\.\.";}
@list l3:level1
	{mso-level-text:%1;
	mso-level-tab-stop:0cm;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l3:level2
	{mso-level-text:"%1\.%2";
	mso-level-tab-stop:21.0pt;
	mso-level-number-position:left;
	margin-left:21.0pt;
	text-indent:-21.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l3:level3
	{mso-level-text:"%1\.%2\.%3";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ascii-font-family:Arial;
	mso-hansi-font-family:Arial;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l3:level4
	{mso-level-text:"%1\.%2\.%3\.%4";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;}
@list l3:level5
	{mso-level-text:"%1\.%2\.%3\.%4\.%5";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l3:level6
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l3:level7
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l3:level8
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l3:level9
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8\.%9";
	mso-level-tab-stop:90.0pt;
	mso-level-number-position:left;
	margin-left:90.0pt;
	text-indent:-90.0pt;}
@list l4
	{mso-list-id:110394034;
	mso-list-type:hybrid;
	mso-list-template-ids:-1797206230 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l4:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l4:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l4:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l4:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l4:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l4:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l4:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l4:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l4:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l5
	{mso-list-id:190730230;
	mso-list-template-ids:1315857002;
	mso-list-style-name:"Style Style Outline numbered Arial 13 pt Bold + Outline numbered A\.\.\.";}
@list l5:level1
	{mso-level-text:%1;
	mso-level-tab-stop:0cm;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l5:level2
	{mso-level-text:"%1\.%2";
	mso-level-tab-stop:21.0pt;
	mso-level-number-position:left;
	margin-left:21.0pt;
	text-indent:-21.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l5:level3
	{mso-level-text:"%1\.%2\.%3";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l5:level4
	{mso-level-text:"%1\.%2\.%3\.%4";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;}
@list l5:level5
	{mso-level-text:"%1\.%2\.%3\.%4\.%5";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l5:level6
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l5:level7
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l5:level8
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l5:level9
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8\.%9";
	mso-level-tab-stop:90.0pt;
	mso-level-number-position:left;
	margin-left:90.0pt;
	text-indent:-90.0pt;}
@list l6
	{mso-list-id:300160897;
	mso-list-type:hybrid;
	mso-list-template-ids:-1458551836 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l6:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l6:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l6:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l6:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l6:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l6:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l6:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l6:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l6:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l7
	{mso-list-id:304164000;
	mso-list-template-ids:275779342;}
@list l7:level1
	{mso-level-text:%1;
	mso-level-tab-stop:21.6pt;
	mso-level-number-position:left;
	margin-left:21.6pt;
	text-indent:-21.6pt;}
@list l7:level2
	{mso-level-text:"%1\.%2";
	mso-level-tab-stop:28.8pt;
	mso-level-number-position:left;
	margin-left:28.8pt;
	text-indent:-28.8pt;}
@list l7:level3
	{mso-level-text:"%1\.%2\.%3";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;}
@list l7:level4
	{mso-level-text:"%1\.%2\.%3\.%4";
	mso-level-tab-stop:43.2pt;
	mso-level-number-position:left;
	margin-left:43.2pt;
	text-indent:-43.2pt;}
@list l7:level5
	{mso-level-text:"%1\.%2\.%3\.%4\.%5";
	mso-level-tab-stop:50.4pt;
	mso-level-number-position:left;
	margin-left:50.4pt;
	text-indent:-50.4pt;}
@list l7:level6
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6";
	mso-level-tab-stop:57.6pt;
	mso-level-number-position:left;
	margin-left:57.6pt;
	text-indent:-57.6pt;}
@list l7:level7
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7";
	mso-level-tab-stop:64.8pt;
	mso-level-number-position:left;
	margin-left:64.8pt;
	text-indent:-64.8pt;}
@list l7:level8
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l7:level9
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8\.%9";
	mso-level-tab-stop:79.2pt;
	mso-level-number-position:left;
	margin-left:79.2pt;
	text-indent:-79.2pt;}
@list l8
	{mso-list-id:323434847;
	mso-list-template-ids:-961394776;}
@list l8:level1
	{mso-level-text:%1;
	mso-level-tab-stop:0cm;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l8:level2
	{mso-level-text:"%1\.%2";
	mso-level-tab-stop:21.0pt;
	mso-level-number-position:left;
	margin-left:21.0pt;
	text-indent:-21.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l8:level3
	{mso-level-text:"%1\.%2\.%3";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;
	mso-ansi-font-size:13.0pt;
	font-family:"Arial",sans-serif;
	mso-bidi-font-family:"Times New Roman";
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l8:level4
	{mso-level-text:"%1\.%2\.%3\.%4";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;}
@list l8:level5
	{mso-level-text:"%1\.%2\.%3\.%4\.%5";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l8:level6
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l8:level7
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l8:level8
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l8:level9
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8\.%9";
	mso-level-tab-stop:90.0pt;
	mso-level-number-position:left;
	margin-left:90.0pt;
	text-indent:-90.0pt;}
@list l9
	{mso-list-id:368066033;
	mso-list-type:hybrid;
	mso-list-template-ids:-136782930 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l9:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l9:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l9:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l9:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l9:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l9:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l9:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l9:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l9:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l10
	{mso-list-id:395015684;
	mso-list-template-ids:1929699812;}
@list l10:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l10:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l10:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l10:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l10:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l10:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l10:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l10:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l10:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l11
	{mso-list-id:403256610;
	mso-list-template-ids:362951122;}
@list l11:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l11:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l11:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l11:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l11:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l11:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l11:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l11:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l11:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l12
	{mso-list-id:454757955;
	mso-list-template-ids:1498557748;}
@list l12:level1
	{mso-level-suffix:space;
	mso-level-text:"Chapter %1";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l12:level2
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l12:level3
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l12:level4
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l12:level5
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l12:level6
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l12:level7
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l12:level8
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l12:level9
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l13
	{mso-list-id:510219671;
	mso-list-template-ids:587119732;}
@list l13:level1
	{mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l13:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l13:level3
	{mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l13:level4
	{mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l13:level5
	{mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l13:level6
	{mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l13:level7
	{mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l13:level8
	{mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l13:level9
	{mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l14
	{mso-list-id:599726681;
	mso-list-template-ids:-164994666;}
@list l14:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l14:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l14:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l14:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l14:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l14:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l14:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l14:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l14:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l15
	{mso-list-id:621884264;
	mso-list-template-ids:-776164860;}
@list l15:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l15:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:"Courier New";
	mso-bidi-font-family:"Times New Roman";}
@list l15:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l15:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l15:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l15:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l15:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l15:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l15:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l16
	{mso-list-id:667372116;
	mso-list-template-ids:1558993730;}
@list l16:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l16:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l16:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l16:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l16:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l16:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l16:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l16:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l16:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l17
	{mso-list-id:754790159;
	mso-list-template-ids:361797504;}
@list l17:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l17:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l17:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l17:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l17:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l17:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l17:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l17:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l17:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l18
	{mso-list-id:966274483;
	mso-list-type:hybrid;
	mso-list-template-ids:-1443830636 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l18:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l18:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l18:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l18:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l18:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l18:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l18:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l18:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l18:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l19
	{mso-list-id:1100487066;
	mso-list-type:hybrid;
	mso-list-template-ids:-1348303402 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l19:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l19:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l19:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l19:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l19:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l19:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l19:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l19:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l19:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l20
	{mso-list-id:1113356139;
	mso-list-type:hybrid;
	mso-list-template-ids:-2064861384 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l20:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l20:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l20:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l20:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l20:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l20:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l20:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l20:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l20:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l21
	{mso-list-id:1217819875;
	mso-list-template-ids:-348233072;}
@list l21:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l21:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l21:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l21:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l21:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l21:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l21:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l21:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l21:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l22
	{mso-list-id:1298954889;
	mso-list-template-ids:1606319404;}
@list l22:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l22:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l22:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l22:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l22:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l22:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l22:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l22:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l22:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l23
	{mso-list-id:1409887029;
	mso-list-template-ids:-1944523404;}
@list l23:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l23:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l23:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l23:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l23:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l23:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l23:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l23:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l23:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l24
	{mso-list-id:1423338542;
	mso-list-template-ids:-465018136;}
@list l24:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l24:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:"Courier New";
	mso-bidi-font-family:"Times New Roman";}
@list l24:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l24:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l24:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l24:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l24:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l24:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l24:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l25
	{mso-list-id:1503855585;
	mso-list-template-ids:185733114;}
@list l25:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l25:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l25:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l25:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l25:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l25:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l25:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l25:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l25:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l26
	{mso-list-id:1515916535;
	mso-list-template-ids:480123262;}
@list l26:level1
	{mso-level-number-format:none;
	mso-level-text:"2\.1";
	mso-level-tab-stop:18.0pt;
	mso-level-number-position:right;
	margin-left:18.0pt;
	text-indent:-18.0pt;}
@list l26:level2
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l26:level3
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l26:level4
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l26:level5
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l26:level6
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l26:level7
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l26:level8
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l26:level9
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l27
	{mso-list-id:1592736680;
	mso-list-template-ids:1498557748;}
@list l27:level1
	{mso-level-suffix:space;
	mso-level-text:"Chapter %1";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l27:level2
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l27:level3
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l27:level4
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l27:level5
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l27:level6
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l27:level7
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l27:level8
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l27:level9
	{mso-level-number-format:none;
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l28
	{mso-list-id:1666401360;
	mso-list-type:hybrid;
	mso-list-template-ids:217491556 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l28:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l28:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l28:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l28:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l28:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l28:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l28:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l28:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l28:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l29
	{mso-list-id:1777553377;
	mso-list-template-ids:-610490052;
	mso-list-style-name:"Style Outline numbered Arial 13 pt Bold";}
@list l29:level1
	{mso-level-text:%1;
	mso-level-tab-stop:21.0pt;
	mso-level-number-position:left;
	margin-left:21.0pt;
	text-indent:-21.0pt;}
@list l29:level2
	{mso-level-text:"%1\.%2";
	mso-level-tab-stop:21.0pt;
	mso-level-number-position:left;
	margin-left:21.0pt;
	text-indent:-21.0pt;}
@list l29:level3
	{mso-level-text:"%1\.%2\.%3";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ascii-font-family:Arial;
	mso-hansi-font-family:Arial;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l29:level4
	{mso-level-text:"%1\.%2\.%3\.%4";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;}
@list l29:level5
	{mso-level-text:"%1\.%2\.%3\.%4\.%5";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l29:level6
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l29:level7
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l29:level8
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l29:level9
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8\.%9";
	mso-level-tab-stop:90.0pt;
	mso-level-number-position:left;
	margin-left:90.0pt;
	text-indent:-90.0pt;}
@list l30
	{mso-list-id:1841388965;
	mso-list-type:hybrid;
	mso-list-template-ids:-1084742018 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l30:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l30:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l30:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l30:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l30:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l30:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l30:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l30:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l30:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l31
	{mso-list-id:1872449838;
	mso-list-type:hybrid;
	mso-list-template-ids:1217553084 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l31:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l31:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l31:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l31:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l31:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l31:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l31:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l31:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l31:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l32
	{mso-list-id:1936130257;
	mso-list-type:hybrid;
	mso-list-template-ids:-215418676 67698689 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l32:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l32:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l32:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l32:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l32:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l32:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l32:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l32:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l32:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l33
	{mso-list-id:1937865286;
	mso-list-template-ids:1741608436;}
@list l33:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l33:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l33:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l33:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l33:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l33:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l33:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l33:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l33:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l34
	{mso-list-id:1996103587;
	mso-list-template-ids:1315857002;
	mso-list-style-id:102380001;}
@list l34:level1
	{mso-level-text:%1;
	mso-level-tab-stop:0cm;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l34:level2
	{mso-level-text:"%1\.%2";
	mso-level-tab-stop:21.0pt;
	mso-level-number-position:left;
	margin-left:21.0pt;
	text-indent:-21.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l34:level3
	{mso-level-text:"%1\.%2\.%3";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ascii-font-family:Arial;
	mso-hansi-font-family:Arial;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l34:level4
	{mso-level-text:"%1\.%2\.%3\.%4";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;}
@list l34:level5
	{mso-level-text:"%1\.%2\.%3\.%4\.%5";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l34:level6
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l34:level7
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l34:level8
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l34:level9
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8\.%9";
	mso-level-tab-stop:90.0pt;
	mso-level-number-position:left;
	margin-left:90.0pt;
	text-indent:-90.0pt;}
@list l35
	{mso-list-id:2023169158;
	mso-list-template-ids:113034268;}
@list l35:level1
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:18.0pt;
	mso-level-number-position:left;
	margin-left:18.0pt;
	text-indent:18.0pt;}
@list l35:level2
	{mso-level-number-format:none;
	mso-level-style-link:"Heading 2";
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l35:level3
	{mso-level-number-format:none;
	mso-level-style-link:"Heading 3";
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l35:level4
	{mso-level-number-format:none;
	mso-level-style-link:"Heading 4";
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l35:level5
	{mso-level-number-format:none;
	mso-level-style-link:"Heading 5";
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l35:level6
	{mso-level-number-format:none;
	mso-level-style-link:"Heading 6";
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l35:level7
	{mso-level-number-format:none;
	mso-level-style-link:"Heading 7";
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l35:level8
	{mso-level-number-format:none;
	mso-level-style-link:"Heading 8";
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l35:level9
	{mso-level-number-format:none;
	mso-level-style-link:"Heading 9";
	mso-level-suffix:none;
	mso-level-text:"";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:0cm;
	text-indent:0cm;}
@list l36
	{mso-list-id:2054426168;
	mso-list-template-ids:-610490052;
	mso-list-style-name:"Style Style Outline numbered Arial 13 pt Bold + Outline numbered A\.\.\.1";}
@list l36:level1
	{mso-level-text:%1;
	mso-level-tab-stop:21.0pt;
	mso-level-number-position:left;
	margin-left:21.0pt;
	text-indent:-21.0pt;
	mso-ansi-font-size:12.0pt;
	mso-ascii-font-family:Arial;
	mso-hansi-font-family:Arial;}
@list l36:level2
	{mso-level-text:"%1\.%2";
	mso-level-tab-stop:21.0pt;
	mso-level-number-position:left;
	margin-left:21.0pt;
	text-indent:-21.0pt;}
@list l36:level3
	{mso-level-text:"%1\.%2\.%3";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ascii-font-family:Arial;
	mso-hansi-font-family:Arial;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l36:level4
	{mso-level-text:"%1\.%2\.%3\.%4";
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;}
@list l36:level5
	{mso-level-text:"%1\.%2\.%3\.%4\.%5";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l36:level6
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6";
	mso-level-tab-stop:54.0pt;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;}
@list l36:level7
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l36:level8
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8";
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;}
@list l36:level9
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8\.%9";
	mso-level-tab-stop:90.0pt;
	mso-level-number-position:left;
	margin-left:90.0pt;
	text-indent:-90.0pt;}
@list l37
	{mso-list-id:2112846673;
	mso-list-template-ids:902971360;}
@list l37:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l37:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l37:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l37:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l37:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l37:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l37:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l37:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l37:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l34:level1 lfo1
	{mso-level-numbering:continue;
	mso-level-tab-stop:7.2pt;
	mso-level-number-position:left;
	margin-left:7.2pt;
	text-indent:0cm;}
@list l34:level2 lfo1
	{mso-level-numbering:continue;
	mso-level-tab-stop:28.2pt;
	mso-level-number-position:left;
	margin-left:28.2pt;
	text-indent:-21.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l34:level3 lfo1
	{mso-level-numbering:continue;
	mso-level-tab-stop:43.2pt;
	mso-level-number-position:left;
	margin-left:43.2pt;
	text-indent:-36.0pt;
	mso-ansi-font-size:13.0pt;
	mso-ascii-font-family:Arial;
	mso-hansi-font-family:Arial;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l34:level4 lfo1
	{mso-level-numbering:continue;
	mso-level-tab-stop:43.2pt;
	mso-level-number-position:left;
	margin-left:43.2pt;
	text-indent:-36.0pt;}
@list l34:level5 lfo1
	{mso-level-numbering:continue;
	mso-level-tab-stop:61.2pt;
	mso-level-number-position:left;
	margin-left:61.2pt;
	text-indent:-54.0pt;}
@list l34:level6 lfo1
	{mso-level-numbering:continue;
	mso-level-tab-stop:61.2pt;
	mso-level-number-position:left;
	margin-left:61.2pt;
	text-indent:-54.0pt;}
@list l34:level7 lfo1
	{mso-level-numbering:continue;
	mso-level-tab-stop:79.2pt;
	mso-level-number-position:left;
	margin-left:79.2pt;
	text-indent:-72.0pt;}
@list l34:level8 lfo1
	{mso-level-numbering:continue;
	mso-level-tab-stop:79.2pt;
	mso-level-number-position:left;
	margin-left:79.2pt;
	text-indent:-72.0pt;}
@list l34:level9 lfo1
	{mso-level-numbering:continue;
	mso-level-tab-stop:97.2pt;
	mso-level-number-position:left;
	margin-left:97.2pt;
	text-indent:-90.0pt;}
ol
	{margin-bottom:0cm;}
ul
	{margin-bottom:0cm;}
-->
</style>
<!--[if gte mso 10]>
<style>
 /* Style Definitions */
 table.MsoNormalTable
	{mso-style-name:"Table Normal";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-noshow:yes;
	mso-style-unhide:no;
	mso-style-parent:"";
	mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
	mso-para-margin:0cm;
	mso-pagination:widow-orphan;
	font-size:10.0pt;
	font-family:"Times New Roman",serif;}
table.MsoTableGrid
	{mso-style-name:"Table Grid";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-unhide:no;
	border:solid windowtext 1.0pt;
	mso-border-alt:solid windowtext .5pt;
	mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
	mso-border-insideh:.5pt solid windowtext;
	mso-border-insidev:.5pt solid windowtext;
	mso-para-margin:0cm;
	mso-pagination:widow-orphan;
	font-size:10.0pt;
	font-family:"Times New Roman",serif;}
</style>
<![endif]--><!--[if gte mso 9]><xml>
 <o:shapedefaults v:ext="edit" spidmax="1026"/>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <o:shapelayout v:ext="edit">
  <o:idmap v:ext="edit" data="1"/>
 </o:shapelayout></xml><![endif]-->
</head>

<body lang=PT-BR link=blue vlink="#954F72" style='tab-interval:7.2pt;
word-wrap:break-word'>

<div class=WordSection1>

<p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
style='font-size:24.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
style='font-size:48.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Linux <o:p></o:p></span></p>

<p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
style='font-size:28.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Server<o:p></o:p></span></p>

<p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
style='font-size:48.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Configuration</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><br
clear=all style='page-break-before:always'>
</span><span class=TimesNewRomanChar><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif'>Table of Contents</span></span><!--[if supportFields]><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><span
style='mso-element:field-begin'></span> INDEX \e &quot;	&quot; \c &quot;1&quot;
\z &quot;1033&quot; <span style='mso-element:field-separator'></span></span><![endif]--><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><span
style='mso-no-proof:yes'><o:p></o:p></span></span></p>

</div>

<span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
mso-fareast-font-family:"Times New Roman";mso-ansi-language:EN-US;mso-fareast-language:
EN-US;mso-bidi-language:AR-SA;mso-no-proof:yes'><br clear=all style='page-break-before:
auto;mso-break-type:section-break'>
</span>

<div class=WordSection2>

<h1><!--[if supportFields]><span lang=EN-US style='font-size:11.0pt;font-family:
"Arial",sans-serif;font-weight:normal;mso-bidi-font-weight:bold'><span
style='mso-element:field-end'></span></span><![endif]--><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif;font-weight:normal;
mso-bidi-font-weight:bold'><a name="_Toc240908184"><o:p>&nbsp;</o:p></a></span></h1>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><!--[if supportFields]><span style='mso-bookmark:_Toc240908184'></span><span
style='mso-element:field-begin'></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold'><span style='mso-spacerun:yes'> </span>TOC \o &quot;1-3&quot; \h \z \u <span
style='mso-element:field-separator'></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><a href="#_Toc242071368"><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'>Chapter
1: Introduction to Linux System Administration</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071368 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>4<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300360038000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071369"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.1 Introduction to UNIX and Linux</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071369 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>4<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300360039000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071370"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.2 Linux command line</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071370 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>4<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300370030000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071371"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.3 Files And Directories</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071371 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>6<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300370031000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071372"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.3.1 List The Names of Files In A Director: ls</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071372 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>7<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300370032000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071373"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.3.2 Viewing And Changing Current Directory: pwd, cd</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071373 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>7<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300370033000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071374"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.3.3 Creating Directory: mkdir</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071374 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>8<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300370034000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071375"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.3.4 Viewing Hidden Files And Directories: ls -a</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071375 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>9<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300370035000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071376"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.4 Working With Files</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071376 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>9<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300370036000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071377"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.4.1 Display A Text File: cat</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071377 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>9<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300370037000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071378"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.4.2 Delete A File: rm</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>.. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071378 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>10<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300370038000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071379"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.4.3 Display A Text File One Screen At A Time: less,
more</span></span><span style='mso-bookmark:_Toc240908184'><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
display:none;mso-hide:screen;mso-bidi-font-weight:bold;mso-no-proof:yes;
text-decoration:none;text-underline:none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071379 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>10<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300370039000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071380"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.4.4 Copy A File: cp</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071380 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>10<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300380030000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071381"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.4.5 Changes The Name Of A File : mv</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071381 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>11<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300380031000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071382"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.4.6 Search For A String In A File: grep</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071382 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>11<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300380032000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071383"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.5 Process Management</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071383 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>12<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300380033000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071384"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.5.1 Process Monitoring: ps</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071384 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>12<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300380034000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071385"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.5.2 Process Monitoring: pstree</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071385 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>12<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300380035000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071386"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.5.3 Process Monitoring: top</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071386 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>13<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300380036000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071387"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.5.4 Signaling Processes</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071387 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>13<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300380037000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071388"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.5.5 Sending Signals: kill</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071388 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>14<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300380038000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071389"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.5.6 Sending Signals to Daemons: pidof</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071389 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>14<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300380039000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071390"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.5.7 Process Priorities: nice</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071390 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>14<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300390030000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071391"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.5.8 Modifying Priorities: renice</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071391 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>15<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300390031000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071392"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.6 Installation of Software in Linux</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071392 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>15<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300390032000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071393"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.6.1 Using apt-get</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071393 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>16<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300390033000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071394"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.6.2 Configuring the sources.list File</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071394 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>16<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300390034000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071395"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.6.3 Using apt-get</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071395 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>18<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300390035000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071396"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.6.8 Installing RPM files</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071396 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>19<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300390036000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc3 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071397"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>1.6.9 Install BIN files</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071397 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>19<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300390037000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071398"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 2: Compressing And Archiving Files</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071398 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>21<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300390038000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071399"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>2.1 Compress A File Using: bzip2</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071399 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>21<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003300390039000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071400"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>2.2 Decompress A File Using: bunzip2</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071400 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>22<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400300030000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071401"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>2.3 Compress A File Using: gzip</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071401 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>22<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400300031000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071402"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>2.4 Archiving Files: tar</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071402 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>22<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400300032000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071403"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 3: Mange File Ownership</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071403 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>25<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400300033000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071404"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>3.1 Users and Groups</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071404 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>25<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400300034000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071405"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>3.2 The Superuser: Root</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071405 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>25<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400300035000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071406"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>3.3 Changing File Ownership: chown</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071406 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>25<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400300036000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071407"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>3.4 Changing File Ownership: chgrp</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071407 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>26<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400300037000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071408"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>3.5 Changing the Ownership of a Directory and Its
Contents</span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
display:none;mso-hide:screen;mso-bidi-font-weight:bold;mso-no-proof:yes;
text-decoration:none;text-underline:none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071408 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>26<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400300038000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071409"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>3.6 Manage File Permission to Control Access to Files</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071409 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>26<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400300039000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071410"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>3.7 Examining Permission of a file: ls l</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071410 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>27<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400310030000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071411"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>3.8 Changing Permissions of Files and Directories: chmod</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071411 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>27<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400310031000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071412"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>3.9 Special Directory Permissions: Sticky</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071412 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>28<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400310032000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071413"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>3.10 Special Directory Permissions: Setgid</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071413 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>29<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400310033000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071414"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 4: FileSystem: Mouning and Unmouning</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071414 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>29<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400310034000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071415"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>4.1 Mounting filesystem: mount</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071415 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>30<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400310035000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071416"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>4.2 Unmounting Filesystem: umount</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071416 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>31<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400310036000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071417"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 5: Managing User Accounts</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071417 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>35<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400310037000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071418"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>5.1 What is an Account?</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071418 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>35<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400310038000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071419"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>5.2 Creating User Account: adduser</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071419 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>35<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400310039000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071420"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>5.3 Changing<span style='mso-spacerun:yes'>  </span>a
Users name: chfn</span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
display:none;mso-hide:screen;mso-bidi-font-weight:bold;mso-no-proof:yes;
text-decoration:none;text-underline:none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071420 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>36<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400320030000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071421"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>5.4 Changing a User Accounts Password: passwd</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071421 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>36<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400320031000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071422"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>5.5 Configuring Group Definitions</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071422 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>38<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400320032000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071423"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>5.6 Creating a Group: groupadd</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071423 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>38<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400320033000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071424"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>5.7 Deleting a Group</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071424 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>38<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400320034000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071425"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>5.8 Adding a member to a group</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071425 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>38<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400320035000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071426"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>5.9 Removing a member from a group</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071426 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>39<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400320036000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071427"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>5.10 Deleting a User Account</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071427 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>39<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400320037000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071428"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 6: Samba File Server</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071428 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>41<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400320038000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071429"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>6.1 Installation</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071429 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>41<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400320039000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071430"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>6.2 Configuration</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071430 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>41<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400330030000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071431"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>6.3 Securing a Samba File and Print Server</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071431 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>43<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400330031000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071432"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 7: Network File System (NFS)</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071432 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>47<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400330032000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071433"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>7.1 Installation</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071433 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>47<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400330033000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071434"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>7.2 Configuration</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071434 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>47<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400330034000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071435"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>7.3 NFS Client Configuration</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071435 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>48<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400330035000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071436"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 8: FTP Server</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071436 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>49<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400330036000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071437"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>8.1 vsftpd - FTP Server Installation</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071437 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>49<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400330037000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071438"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>8.2 Anonymous FTP Configuration</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071438 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>49<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400330038000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071439"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>8.3 User Authenticated FTP Configuration</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071439 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>50<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400330039000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071440"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>8.4 Securing FTP</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071440 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>50<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400340030000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071441"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 9: Dynamic Host Configuration Protocol (DHCP)</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071441 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>53<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400340031000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071442"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>9.1 Installation</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071442 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>54<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400340032000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071443"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>9.2 Configuration</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071443 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>54<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400340033000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071444"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 10: Squid - Proxy Server</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071444 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>56<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400340034000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071445"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>10.1 Installation</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071445 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>56<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400340035000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071446"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>10.2 Configuration</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071446 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>56<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400340036000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071447"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 11: DNS</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071447 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>59<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400340037000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071448"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>11.1 Installation</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071448 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>59<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400340038000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071449"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>11.2 Configuration</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071449 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>59<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400340039000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071450"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>11.3 Overview</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>.. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071450 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>59<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400350030000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071451"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 12: HTTPD - Apache2 Web Server</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071451 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>64<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400350031000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071452"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>12.1 Installation</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071452 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>64<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400350032000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071453"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>12.2 Configuration</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071453 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>64<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400350033000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071454"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>12.3 Basic Settings</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071454 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>65<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400350034000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071455"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>12.4 Default Settings</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071455 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>67<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400350035000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071456"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>12.5 httpd Settings</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071456 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>69<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400350036000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071457"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 13: MySQL</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071457 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>72<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400350037000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071458"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>13.1 Installation</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071458 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>72<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400350038000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071459"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>13.2 Configuration</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071459 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>72<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400350039000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc1 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071460"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>Chapter 14: Postfix (Mail server)</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'> </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071460 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>74<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400360030000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071461"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>14.1 Installation</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071461 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>74<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400360031000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071462"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>14.2 Basic Configuration</span></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071462 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>74<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400360032000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<p class=MsoToc2 style='tab-stops:right dotted 431.5pt'><span style='mso-bookmark:
_Toc240908184'></span><a href="#_Toc242071463"><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;mso-bidi-font-weight:
bold;mso-no-proof:yes'>14.3 Testing</span></span><span style='mso-bookmark:
_Toc240908184'><span lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;
color:windowtext;display:none;mso-hide:screen;mso-bidi-font-weight:bold;
mso-no-proof:yes;text-decoration:none;text-underline:none'><span
style='mso-tab-count:1 dotted'>. </span></span></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-begin'></span><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'> PAGEREF _Toc242071463 \h </span></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif;color:windowtext;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'><span style='display:none;mso-hide:screen'><span style='mso-element:field-separator'></span></span></span></span><![endif]--><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;color:windowtext;display:none;mso-hide:screen;
mso-bidi-font-weight:bold;mso-no-proof:yes;text-decoration:none;text-underline:
none'>75<!--[if gte mso 9]><xml>
 <w:data>08D0C9EA79F9BACE118C8200AA004BA90B02000000080000000E0000005F0054006F0063003200340032003000370031003400360033000000</w:data>
</xml><![endif]--></span></span><!--[if supportFields]><span style='mso-bookmark:
_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'></span></a><span
style='mso-bookmark:_Toc240908184'><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif;mso-bidi-font-weight:bold;mso-no-proof:yes'><o:p></o:p></span></span></p>

<h1><span style='mso-bookmark:_Toc240908184'></span><!--[if supportFields]><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-element:field-end'></span><![endif]--><span
style='mso-bookmark:_Toc240908184'></span><span style='mso-bookmark:_Toc240908184'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman";font-weight:normal;mso-bidi-font-weight:bold'><br clear=all
style='page-break-before:always'>
</span><a name="_Toc242071368"><span lang=EN-US>Chapter 1: Introduction to
Linux System Administration</span></a></span></h1>

<h2><span style='mso-bookmark:_Toc240908184'><span lang=EN-US><o:p>&nbsp;</o:p></span></span></h2>

<h2><span style='mso-bookmark:_Toc240908184'><a name="_Toc242071369"><span
lang=EN-US>1.1 Introduction to UNIX and Linux</span></a></span><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-begin'></span> XE &quot;Introduction
to UNIX and Linux&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--></h2>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Linux
is a true 32-bit operating system that runs on a variety of different
platforms, including Intel, Sparc, Alpha, and Power-PC (on some of these
platforms, such as Alpha, Linux is actually 64-bit). <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Linux
was first developed back in the early 1990s, by a young Finnish then-university
student named Linus Torvalds. Linus had a <span class=quote>&quot;state-of-the-art&quot;</span>
386 box at home and decided to write an alternative to the 286-based Minix
system (a small UNIX-like implementation primarily used in operating systems
classes), to take advantage of the extra instruction set available on the
then-new chip, and began to write a small bare-bones kernel.<o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
interesting thing about Linux is, it is completely free! Linus decided to adopt
the GNU Copyleft license of the Free Software Foundation, which means that the
code is protected by a copyright -- but protected in that it must always be available
to others.<o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Free
means <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>free</span></em> -- you can get it for free, use it for
free, and you are even free to sell it for a profit (this isn't as strange as
it sounds; several organizations, including Red Hat, have packaged up the
standard Linux kernel, a collection of GNU utilities, and put their own <span
class=quote>&quot;flavor&quot;</span> of included applications, and sell them
as distributions. Some common and popular distributions are Slackware, Ubuntu,
Red Hat, SuSe, and Debian)! The great thing is, you have access to source code
which means you can customize the operating systems to your <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>own</span></em>
needs, not those of the <span class=quote>&quot;target market&quot;</span> of
most commercial vendors. Among most of the distributions Ubuntu is now very
popular. It provides very simple gui facilities and a good command line
interface. For the purpose of our demonstration examples we will use this
operating system.<o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Linux
can and should be considered a full-blown implementation of UNIX. However, it
can not be called <span class=quote>&quot;Unix&quot;</span>; not because of
incompatibilities or lack of functionality, but because the word <span
class=quote>&quot;Unix&quot;</span> is a registered trademark owned by
AT&amp;T, and the use of the word is only allowable by license agreement. Linux
is every bit as supported, as reliable, and as viable as any other operating
system solution. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908185"></a><a name="_Toc242071370"><span style='mso-bookmark:
_Toc240908185'><span lang=EN-US>1.2 Linux command line</span></span></a></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>When Linus Torvalds introduced Linux and for a long time
thereafter, Linux did not have a graphical user interface (GUI): I ran on
character-based terminals only. All the tools ran from a command line. Today
the Linux GUI is important but many peopleespecially system administratorsrun
many command line programs. Command line utilities are often faster, more
powerful, or more complete than their GUI counterparts. Sometimes there is no
GUI counterpart to a textual utility; some people just prefer the hands-on
feeling of the command line. When you work with a command line interface, you
are working with a shell.<o:p></o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>A shell provides an interface between the user and operating
system kernel. It is a command interpreter that takes commands from users and
executes it.<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Linuxs most common command interpreter is called <b
style='mso-bidi-font-weight:normal'>bash</b>. <b style='mso-bidi-font-weight:
normal'>Bash</b> is the abbreviation of <b style='mso-bidi-font-weight:normal'>Bourne-Again
Shell</b>. <o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The shell is where commands are invoked. When started, the
bash shell gives us a prompt and waits for a command to be entered. The command
is typed at the shell prompt. The prompt usually ends in a dollar sign ($).
After typing a command we need to press </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ENTER</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to invoke it. The
shell will execute the command. Another prompt will then appear. <o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Shell commands consist of one or more words separated by
spaces. The first word is the command to be run. Subsequent words are either
options or arguments to the command. Options usually start with one or two
hyphens.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Some examples of commands:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l20 level1 lfo2;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>List all the &#64257;les in the
     current directory:<o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>$<span style='mso-spacerun:yes'>  </span></span><b
style='mso-bidi-font-weight:normal'><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>ls</span></b><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l20 level1 lfo2;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>List the &#64257;les in the long
     format (giving more information):<o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>$<span style='mso-spacerun:yes'>  </span></span><b
style='mso-bidi-font-weight:normal'><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>ls l<o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l20 level1 lfo2;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>List full information about some
     speci&#64257;c &#64257;les:<o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>$<span style='mso-spacerun:yes'>  </span></span><b
style='mso-bidi-font-weight:normal'><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>ls -l notes.txt report.txt</span></b><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l20 level1 lfo2;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>List full information about all
     the .txt &#64257;les:<o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>$<span style='mso-spacerun:yes'>  </span></span><b
style='mso-bidi-font-weight:normal'><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>ls -l *.txt</span></b><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l20 level1 lfo2;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>List all &#64257;les in long
     format, even the hidden ones:<o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>$<span style='mso-spacerun:yes'>  </span></span><b
style='mso-bidi-font-weight:normal'><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>ls -l -a</span></b><b style='mso-bidi-font-weight:
normal'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:18.0pt;text-indent:18.0pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>$<span style='mso-spacerun:yes'>  </span></span><b
style='mso-bidi-font-weight:normal'><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>ls -la</span></b><b style='mso-bidi-font-weight:
normal'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p></o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The dollar ($) represents the prompt
here. We need not type it.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Most command take <b style='mso-bidi-font-weight:
normal'>parameters</b>. Some commands require them. Parameters are also known
as <b style='mso-bidi-font-weight:normal'>arguments</b>. For example the
command </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>echo</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> simply displays its arguments.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><span style='mso-tab-count:1'>   </span><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>echo</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>echo hello there</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>hello there<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The first </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>echo</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command outputs a
blank line and the second </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>echo</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command outputs its arguments.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Commands are usually case sensitive.
Most of the commands are in lower case. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>echo whisper<o:p></o:p></b></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>whisper<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ECHO shout</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>bash: ECHO: command not
found<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Often it is desired to repeat a previously executed command.
The shell keeps a <b style='mso-bidi-font-weight:normal'>command history </b>for
this purpose. <o:p></o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='text-align:justify;mso-list:l20 level1 lfo2;
     tab-stops:list 36.0pt'><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>We
     use </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>UP</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> and </span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>DOWN</span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'> to scroll through the list of
     previously executed commands and then press </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Courier New"'>ENTER</span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
     to execute the desired command. <o:p></o:p></span></li>
 <li class=MsoNormal style='text-align:justify;mso-list:l20 level1 lfo2;
     tab-stops:list 36.0pt'><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Commands
     can also be edited before being run. The </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Courier New"'>LEFT</span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
     and </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>RIGHT</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> cursor keys navigate across a command. <o:p></o:p></span></li>
 <li class=MsoNormal style='text-align:justify;mso-list:l20 level1 lfo2;
     tab-stops:list 36.0pt'><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Extra
     characters can be typed at any point. </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Courier New"'>BACKSPACE</span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
     deletes characters to the left of the cursor. </span><st1:place w:st="on"><st1:State
      w:st="on"><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
       mso-bidi-font-family:"Courier New"'>DEL</span></st1:State></st1:place><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'> and </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Courier New"'>CTRL+D </span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>delete
     characters to the right.<o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Typically successful commands do not give any output.
However, messages are displayed in the case of errors.<b><o:p></o:p></b></span></p>

<p class=MsoNormal style='text-align:justify'><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<h2><a name="_Toc242071371"><span lang=EN-US>1.3 </span></a><a
name="_Toc240908186"><span style='mso-bookmark:_Toc242071371'><span lang=EN-US>Files
And Directories</span></span></a></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>A directory is a collection of files and/or other
directories. Because a directory can contain other directories, we get a
directory <b style='mso-bidi-font-weight:normal'>hierarchy</b>. The top level
of the hierarchy is the <b style='mso-bidi-font-weight:normal'>root directory</b>.
Files and directories can be named by a <b style='mso-bidi-font-weight:normal'>path.
</b>The root directory is referred to as /. Other directories are referred to
by the <b style='mso-bidi-font-weight:normal'>path</b>. The <b
style='mso-bidi-font-weight:normal'>path </b>consists of names separated by /.
A file can also be referred to by the <b style='mso-bidi-font-weight:normal'>path</b>.
If it is directory, then the <b style='mso-bidi-font-weight:normal'>path </b>may
end with a /.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><span
style='mso-spacerun:yes'> </span>An <b style='mso-bidi-font-weight:normal'>absolute
path </b>starts at the root of the directory hierarchy and names directories or
files under it. For example: <span style='mso-tab-count:1'>   </span><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>/</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>etc/hostname</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The above refers to a file </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>hostname</span><b style='mso-bidi-font-weight:normal'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> </span></b><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>which
is in the </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>etc</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> directory under the root (/) directory.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908187"></a><a name="_Toc242071372"><span style='mso-bookmark:
_Toc240908187'><span lang=EN-US>1.3.1 List The Names of Files In A Director: ls</span></span></a></h3>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>We can use </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command to list
files in a specific directory by specifying the specific directory:<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls /usr/share/doc/<o:p></o:p></b></span></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The above command lists all he files
and folders under the directory </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/usr/share/doc.</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> If the first argument to </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> is not given,
then </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>ls</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
lists the files in current working directory of he user.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>-l</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> option to </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> gives more
information, including the size of &#64257;les and the date they were last
modi&#64257;ed:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l<o:p></o:p></b></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>drwxrwxr-x 2 fred users 4096
Jan 21 <st1:time Minute="57" Hour="10" w:st="on">10:57</st1:time> Accounts<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-rw-r-- 1 fred users 345
Jan 21 <st1:time Minute="57" Hour="10" w:st="on">10:57</st1:time> notes.txt<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r-- 1 fred users 3255
Jan 21 <st1:time Minute="57" Hour="10" w:st="on">10:57</st1:time> report.txt<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908188"></a><a name="_Toc242071373"><span style='mso-bookmark:
_Toc240908188'><span lang=EN-US>1.3.2 Viewing And Changing Current Directory:
pwd, cd</span></span></a></h3>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The shell has a <b style='mso-bidi-font-weight:normal'>current
directory  </b>the directory in which currently the logged user is working in
shell. Usually after firs login, the current directory should be the home
directory of the user. Some commands like </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>use the current
directory if none is specified. We use </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>pwd</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command to see
what the current directory is:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>pwd</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>/home/fred<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>We can change the current directory
with the command<span style='mso-spacerun:yes'>  </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>cd :<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><span style='mso-tab-count:1'>   </span></span><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd</b> /<b style='mso-bidi-font-weight:normal'>mnt/cdrom</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>pwd</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>/mnt/cdrom<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The symbol tlide (~) is an abbreviation
for home directory. So for user fred the following are equivalent:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd /home/fred/documents</b>/<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd /documents/<o:p></o:p></b></span></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The following are the same for user
fred:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd<o:p></o:p></b></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd <o:p></o:p></b></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd /home/fred<o:p></o:p></b></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Paths do not have to start from the root directory. A path
which does not start with the / is a <b style='mso-bidi-font-weight:normal'>relative
path</b>. It is relative to some other directory usually current directory.
Relative paths specify files in the same way as the absolute ones. For example
the following sets of directory changes end up in the same directory<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd /usr/share/doc<o:p></o:p></b></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd /</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd usr</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd share/doc<o:p></o:p></b></span></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Every directory contains two special
filenames which help making relative paths. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The directory<span
style='mso-spacerun:yes'>  </span></span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>.. </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>points to the parent directory. </span><b style='mso-bidi-font-weight:
normal'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>ls .. </span></b><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>will list files in the parent directory<o:p></o:p></span></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>For example if we start from </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/home/fred:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd ..</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>pwd</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>/home<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd ..<o:p></o:p></b></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>pwd</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>/<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The directory<span
style='mso-spacerun:yes'>  </span></span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>. </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>points to the directory it is in. sp </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>./foo</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> is the same file
as </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>foo</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The special </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>..</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> and </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>.</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> directories can
be used in paths just like any other directory names:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cd ../other-dir/<o:p></o:p></b></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The above means the directory </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>other-dir </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>in the
parent directory of the current directory.<span style='mso-spacerun:yes'> 
</span>It is common to see </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>.. </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>to go back several directories from the current directory.
The dot directory is most commonly used on its own to mean the current
directory. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908189"></a><a name="_Toc242071374"><span style='mso-bookmark:
_Toc240908189'><span lang=EN-US>1.3.3 Creating Directory: mkdir</span></span></a></h3>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>mkdir</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command makes new
directory under an existing directory. For example to create a directory for
storing music files:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>mkdir musics<o:p></o:p></b></span></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To delete an empty directory we use </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>rmdir</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>rmdir OldMusics<o:p></o:p></b></span></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>We use </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>rm</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> with r option to
delete directories and all the files (recursively) they contain.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:28.8pt;text-indent:7.2pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>$<span style='mso-spacerun:yes'>  </span></span><b
style='mso-bidi-font-weight:normal'><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>rm -r OldMusics<o:p></o:p></span></b></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908190"></a><a name="_Toc242071375"><span style='mso-bookmark:
_Toc240908190'><span lang=EN-US>1.3.4 Viewing Hidden Files And Directories: ls
-a</span></span></a></h3>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The special</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'> .</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> and </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>..</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> directories dont
show up when we do </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>ls.</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> They are <b style='mso-bidi-font-weight:normal'>hidden
files</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Files whose name starts with a dot ( </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>.</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> ) are considered
hidden. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Make </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to list all
files, even the hidden ones, by giving the </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>a</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> option:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -a</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>. .. .bashrc .profile
report.doc<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<h2><a name="_Toc240908191"></a><a name="_Toc242071376"><span style='mso-bookmark:
_Toc240908191'><span lang=EN-US>1.4 Working With Files</span></span></a></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>This section describes utilities that
copy, move, print, search through, display, sort, and compare files.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908192"></a><a name="_Toc242071377"><span style='mso-bookmark:
_Toc240908192'><span lang=EN-US>1.4.1 Display A Text File: </span></span></a><span
style='mso-bookmark:_Toc242071377'><span style='mso-bookmark:_Toc240908192'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>cat</span></span></span></h3>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>cat</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> utility displays the contents of a text file. The name of
the command is derived from catenate, which means to join together, one after
the other. A convenient way to display the contents of a file to the screen is
by giving the command </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>cat</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, followed by a SPACE and the filename. Figure 1.5.1 shows </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>cat</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> displaying the
contents of practice. This figure shows the difference between the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> and cat utilities:
The </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>ls</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
utility displays the name of a file, whereas </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>cat</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> displays the
contents of a file.<o:p></o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908193"></a><a name="_Toc242071378"><span style='mso-bookmark:
_Toc240908193'><span lang=EN-US>1.4.2 Delete A File: </span></span></a><span
style='mso-bookmark:_Toc242071378'><span style='mso-bookmark:_Toc240908193'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>rm</span></span></span></h3>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>rm</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> (remove) utility deletes a file. Figure 1 shows rm deleting
the file named </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>practice</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. After </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>rm</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> deletes the file,<span style='mso-spacerun:yes'>  </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> and </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>cat</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> show that
practice is no longer in the directory. The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> utility does not
list its filename, and cat says that no such file exists.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Use </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>rm</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> carefully.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>practice<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cat practice</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>This is a small file that I
created<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>with a text editor.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>rm practice</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls<o:p></o:p></b></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cat practice</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>cat: practice: No such file
or directory<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908194"></a><a name="_Toc242071379"><span style='mso-bookmark:
_Toc240908194'><span lang=EN-US>1.4.3 Display A Text File One Screen At A Time:
</span></span></a><span style='mso-bookmark:_Toc242071379'><span
style='mso-bookmark:_Toc240908194'><span lang=EN-US style='mso-bidi-font-family:
"Courier New"'>less, more</span></span></span></h3>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>When you want to view a file that is longer than one screen,
you can use either the </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>less</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> utility or the </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>more</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> utility. Each of these utilities pauses after displaying a
screen of text. Because these utilities show one page at a time, they are
called pagers. Although </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>less</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> and </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>more</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> are very similar, they have subtle differences. At the end
of the file, for example, </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>less</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> displays an EOF (end of file) message and waits for you to
press </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>q</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
before returning you to the shell. In contrast, </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>more</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> returns you
directly to the shell. In both utilities you can press </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>h</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to display a Help
screen that lists commands you can use while paging through a file. For
example:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><tt><span lang=EN-US
style='font-size:11.0pt'>$<b> more </b></span></tt><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>target-file(s) <o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>displays
the contents of <i>target-file(s)&nbsp;</i> on the screen, pausing at the end
of each screenful and asking the user to press a key (useful for long files).
It also incorporates a searching facility (press '<tt><span style='mso-ansi-font-size:
11.0pt;mso-bidi-font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>/</span></tt>' and then type a phrase that you want to look
for). <o:p></o:p></span></p>

<p style='margin-left:21.6pt;text-indent:7.2pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908195"></a><a name="_Toc242071380"><span style='mso-bookmark:
_Toc240908195'><span lang=EN-US>1.4.4 Copy A File: </span></span></a><span
style='mso-bookmark:_Toc242071380'><span style='mso-bookmark:_Toc240908195'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>cp</span></span></span></h3>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The cp (copy) utility (Figure 1.6.1) makes a copy of a file.
This utility can copy any file, including text and executable program (binary)
files. You can use cp to make a backup copy of a file or a copy to experiment
with. The cp command line uses the following syntax to specify source and
destination files:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><b style='mso-bidi-font-weight:
normal'><span lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>cp<i
style='mso-bidi-font-style:normal'> source-file destination-file<o:p></o:p></i></span></b></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The <b style='mso-bidi-font-weight:
normal'><i style='mso-bidi-font-style:normal'>source-file</i></b> is the name
of the file that </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>cp</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> will copy. The <b style='mso-bidi-font-weight:normal'><i
style='mso-bidi-font-style:normal'>destination-file</i></b> is the name that </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>cp</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> assigns to the
resulting (new) copy of the file.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>memo <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cp memo memo.copy</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>memo memo.copy<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>c</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>p command line in Figure 1.6.1 copies the file named </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>memo</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>memo.copy</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>. The
period is part of the filenamejust another character. The initial </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command shows
that </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>memo</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> is the only file in the directory. After the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>cp</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command, second </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> shows two files
in the directory, </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>memo</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> and </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>memo.copy</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>.<o:p></o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908196"></a><a name="_Toc242071381"><span style='mso-bookmark:
_Toc240908196'><span lang=EN-US>1.4.5 Changes The Name Of A File : </span></span></a><span
style='mso-bookmark:_Toc242071381'><span style='mso-bookmark:_Toc240908196'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>mv</span></span></span></h3>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>mv</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> (move) utility
can rename a file without making a copy of it. The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>mv</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command line
specifies an existing file and a new filename using the same syntax as </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>cp</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><b style='mso-bidi-font-weight:
normal'><span lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>mv<i
style='mso-bidi-font-style:normal'> existing-filename new-filename<o:p></o:p></i></span></b></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The command line in Figure 1.6.2
changes the name of the file </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>memo</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> to </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>memo.0130</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>.<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The initial </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>ls</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command shows that </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>memo</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> is the only file
in the directory. After you give the </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>mv</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command, </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>memo.0130</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> is the only file in the directory. Compare this result to
that of the earlier </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>cp</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> example.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>memo<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>mv memo memo.0130</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>memo.0130<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908197"></a><a name="_Toc242071382"><span style='mso-bookmark:
_Toc240908197'><span lang=EN-US>1.4.6 Search For A String In A File: </span></span></a><span
style='mso-bookmark:_Toc242071382'><span style='mso-bookmark:_Toc240908197'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>grep</span></span></span></h3>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>grep</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> utility searches
through one or more files to see whether any contain a specified string of
characters. This utility does not change the file it searches but simply
displays each line that contains the string.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>cat memo</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Helen:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>In our meeting on June 6 we<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>discussed the issue of
credit.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Have you had any further
thoughts<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>about it?<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>           </span><span style='mso-tab-count:4'>    </span><span
style='mso-spacerun:yes'> </span>Alex<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>grep 'credit' memo</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>discussed the issue of
credit.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>grep</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command in Figure 1.6.3 searches through the file </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>memo</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> for lines that
contain the string </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>credit</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> and displays a single line that meets this criterion. If </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>memo</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> contained such
words as </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>discredi</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>t, </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>creditor</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, or </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>accreditation</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>grep</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> would have displayed those lines as well because they
contain the string it was searching for. The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>w</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> option causes </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>grep</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to match only
whole words. Although you do not need to enclose the string you are searching
for in single quotation marks, doing so allows you to put SPACEs and special
characters in the search string. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908198"></a><a name="_Toc242071383"><span style='mso-bookmark:
_Toc240908198'><span lang=EN-US>1.5 Process Management</span></span></a></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The kernel considers each program running on our system to
be a <b style='mso-bidi-font-weight:normal'>process</b>. A process lives as
it executes with a lifetime that may be short or long. A process is said to die
when it terminates. The kernel identifies each process by a number known as
process id, or <b style='mso-bidi-font-weight:normal'>pid. </b>A process has a
user id(</span><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>uid</span></b><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>) and
a group id(</span><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>gid</span></b><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>)
which together specifies what permissions it has. A process has a parent
process id (</span><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ppid</span></b><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>) 
the </span><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>pid</span></b><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> of
the process that has created it. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Each process has its own working
directory initially inherited from its parent process. There is an environment
for each process. A collection of named environment variables and their
associated values. The environment is usually inherited from the parent
process. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908199"></a><a name="_Toc242071384"><span style='mso-bookmark:
_Toc240908199'><span lang=EN-US>1.5.1 Process Monitoring: </span></span></a><span
style='mso-bookmark:_Toc242071384'><span style='mso-bookmark:_Toc240908199'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>ps</span></span></span></h3>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><span
style='mso-spacerun:yes'> </span><o:p></o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ps</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command gives a
snapshot of the processes running on the system at a given moment in time. It
normally shows a brief summary of each process. The command </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ps</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> has many options.
Some of the most commonly used are:<o:p></o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l20 level1 lfo2;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>-a  Show processes owned by other
     users<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l20 level1 lfo2;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>-f  display process ancestors in
     a tree-like format<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l20 level1 lfo2;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>-u  use the user output format,
     showing user names and process start times<o:p></o:p></span></li>
</ul>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908200"></a><a name="_Toc242071385"><span style='mso-bookmark:
_Toc240908200'><span lang=EN-US>1.5.2 Process Monitoring: </span></span></a><span
style='mso-bookmark:_Toc242071385'><span style='mso-bookmark:_Toc240908200'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>pstree</span></span></span></h3>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>It also displays a snapshot of
currently running processes. It always uses a tree like display similar to </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ps f </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>. Some
of the most commonly used options for </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>pstree</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> are:<o:p></o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l28 level1 lfo3;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman";mso-bidi-font-weight:bold'>-a 
     displays commands arguments<b><o:p></o:p></b></span></li>
 <li class=MsoNormal style='mso-list:l28 level1 lfo3;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman";mso-bidi-font-weight:bold'>-c 
     dont compact identical subtrees<b><o:p></o:p></b></span></li>
 <li class=MsoNormal style='mso-list:l28 level1 lfo3;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman";mso-bidi-font-weight:bold'>-G 
     attempts to use terminal specific line-drawing characters<b><o:p></o:p></b></span></li>
 <li class=MsoNormal style='mso-list:l28 level1 lfo3;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman";mso-bidi-font-weight:bold'>-h 
     highlights the ancestors of the current process<b><o:p></o:p></b></span></li>
 <li class=MsoNormal style='mso-list:l28 level1 lfo3;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman";mso-bidi-font-weight:bold'>-n 
     sort processes numerically by pid, rather then alphabetically by name<b><o:p></o:p></b></span></li>
 <li class=MsoNormal style='mso-list:l28 level1 lfo3;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman";mso-bidi-font-weight:bold'>-p 
     includes pid in the output<b><o:p></o:p></b></span></li>
</ul>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman";mso-bidi-font-weight:bold'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908201"></a><a name="_Toc242071386"><span style='mso-bookmark:
_Toc240908201'><span lang=EN-US>1.5.3 Process Monitoring: </span></span></a><span
style='mso-bookmark:_Toc242071386'><span style='mso-bookmark:_Toc240908201'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>top</span></span></span></h3>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The top command shows full-screen, continuously updated
snapshots of process activity. It wais for a short period of time between each
snapshots to give the illusion of real-time monitoring. Processes are displayed
in descending order of how much processor time they are using. It also displays
system uptime, load average, cpu status and memory information. Some of the
most commonly used options for </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>top</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> are:<o:p></o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l6 level1 lfo4;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>-b</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>  Batch mode  send snapshots to standard output<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l6 level1 lfo4;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>-n num</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>  Exit after displaying num snapshots<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l6 level1 lfo4;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>-d delay</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>  Wait delay seconds between each snapshot<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l6 level1 lfo4;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>-i </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'><span style='mso-spacerun:yes'> </span> Ignore idle
     processes<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l6 level1 lfo4;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>s</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'><span style='mso-spacerun:yes'>  </span> Disable
     interactive commands which could be dangerous the superuser<o:p></o:p></span></li>
</ul>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908202"></a><a name="_Toc242071387"><span style='mso-bookmark:
_Toc240908202'><span lang=EN-US>1.5.4 Signaling Processes</span></span></a></h3>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>A process can be sent a signal by the kernel or by another
process. Each signal is a very simple message: A small whole number with a
mnemonic name. Signal names are all-capitals like </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>INT</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>. they are often
written with </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>SIG</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> as part of the name for example: </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>SIGINT</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>.
There are about 30 signals available not all of which are useful. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The following are the most commonly
used signals:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='margin-left:47.6pt;border-collapse:collapse;border:none;mso-border-alt:
 solid windowtext .5pt;mso-yfti-tbllook:480;mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
 mso-border-insideh:.5pt solid windowtext;mso-border-insidev:.5pt solid windowtext'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes'>
  <td width=59 valign=top style='width:43.95pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Name<o:p></o:p></span></p>
  </td>
  <td width=77 valign=top style='width:57.85pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Number <o:p></o:p></span></p>
  </td>
  <td width=324 valign=top style='width:243.0pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Meaning<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1'>
  <td width=59 valign=top style='width:43.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>INT<o:p></o:p></span></p>
  </td>
  <td width=77 valign=top style='width:57.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>2<o:p></o:p></span></p>
  </td>
  <td width=324 valign=top style='width:243.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Interrupt  stop running. Sent by the
  kernel when<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>you press Ctrl+C in a terminal.<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2'>
  <td width=59 valign=top style='width:43.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>TERM<o:p></o:p></span></p>
  </td>
  <td width=77 valign=top style='width:57.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>15<o:p></o:p></span></p>
  </td>
  <td width=324 valign=top style='width:243.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Please terminate. Used to ask a
  process to exit<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>gracefully.<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3'>
  <td width=59 valign=top style='width:43.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>KILL<o:p></o:p></span></p>
  </td>
  <td width=77 valign=top style='width:57.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>9<o:p></o:p></span></p>
  </td>
  <td width=324 valign=top style='width:243.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Die! Forces the process to stop
  running; it is given<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>no opportunity to clean up after
  itself.<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:4'>
  <td width=59 valign=top style='width:43.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>TSTP<span style='mso-spacerun:yes'> 
  </span><o:p></o:p></span></p>
  </td>
  <td width=77 valign=top style='width:57.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>18<o:p></o:p></span></p>
  </td>
  <td width=324 valign=top style='width:243.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Requests the process to stop itself
  temporarily. Sent<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>by the kernel when you press Ctrl+Z
  in a terminal.<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:5;mso-yfti-lastrow:yes'>
  <td width=59 valign=top style='width:43.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>HUP<o:p></o:p></span></p>
  </td>
  <td width=77 valign=top style='width:57.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>1<o:p></o:p></span></p>
  </td>
  <td width=324 valign=top style='width:243.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Hang up. Sent by the kernel when we
  log out, or<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>disconnect a modem. Conventionally
  used by many<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>daemons as an instruction to re-read
  a con&#64257;guration<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>&#64257;le.<o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908203"></a><a name="_Toc242071388"><span style='mso-bookmark:
_Toc240908203'><span lang=EN-US>1.5.5 Sending Signals:</span></span></a><span
style='mso-bookmark:_Toc242071388'><span style='mso-bookmark:_Toc240908203'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'> kill</span></span></span></h3>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The kill command is used to send a signal to a process It is
a normal executable command, but many shells also provide it as a built-in. For
example to send a SIGHUP signal to a process we use either of the following
two:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>kill -HUP pid </b>or <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>kill -s HUP pid<o:p></o:p></b></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><b style='mso-bidi-font-weight:
normal'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>If we omit out the signal name in the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>kill</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command, by
default </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>kill</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> will send a SIGTERM<span style='mso-spacerun:yes'> 
</span>to the process. We can specify more than one </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>pid</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to signal
multiple processes at the same time. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908204"></a><a name="_Toc242071389"><span style='mso-bookmark:
_Toc240908204'><span lang=EN-US>1.5.6 Sending Signals to Daemons:</span></span></a><span
style='mso-bookmark:_Toc242071389'><span style='mso-bookmark:_Toc240908204'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'> pidof</span></span></span></h3>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>On UNIX systems, long-lived processes
that provide some service are often referred to as<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>daemons. Daemons typically have a con&#64257;guration
&#64257;le (usually under </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>) which affects their behavior. Many daemons read their
con&#64257;guration &#64257;le only at startup. If the con&#64257;guration
changes, you have to explicitly tell the daemon by sending it a SIGHUP signal.
We can sometimes use </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>pidof</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> to &#64257;nd the dæmons pid: for example, to tell the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>inetd</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> dæmon to reload
its con&#64257;guration, we can run:<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>kill -HUP $(pidof /usr/sbin/inetd)<o:p></o:p></b></span></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908205"></a><a name="_Toc242071390"><span style='mso-bookmark:
_Toc240908205'><span lang=EN-US>1.5.7 Process Priorities: nice</span></span></a></h3>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Not all tasks require the same amount of execution time.
Linux has the concept of execution priority to deal with this. Process priority
is dynamically altered by the kernel. We can view the current priority by
looking at </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>top</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> or </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>ps -l</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> and looking at the PRI column. The priority can be biased
using </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>nice.</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> The current bias can be seen in the NI column in </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>top.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>nice</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command starts a program with a given priority bias.
Peculiar name: nicer processes require fewer resources. Niceness ranges from
+19 (very nice) to &#8722;20 (not very nice). Non-root users can only specify
values from 1 to 19; the root user can specify the full range of values.
Default niceness when using nice is 10.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To run a command at increased niceness
(lower priority):<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>nice -10 long-running-command &amp;</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>nice -n 10 long-running-command &amp;<o:p></o:p></b></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To run a command at decreased niceness
(higher priority):<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>nice --15 important-command &amp;<o:p></o:p></b></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>nice -n -15 important-command &amp;<o:p></o:p></b></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908206"></a><a name="_Toc242071391"><span style='mso-bookmark:
_Toc240908206'><span lang=EN-US>1.5.8 Modifying Priorities: </span></span></a><span
style='mso-bookmark:_Toc242071391'><span style='mso-bookmark:_Toc240908206'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>renice</span></span></span></h3>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The command</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'> renice</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
changes the niceness of existing processes. Non-root users are only permitted
to increase a processs niceness. To set the process with pid 2984 to a higher
niceness (lower priority):<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>renice 15 2984</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The niceness is just a number: no extra
 sign. To set the process with pid 3598 to a lower niceness (higher priority):<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><span style='mso-tab-count:1'>   </span><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>renice -15 3598</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>You can also change the niceness of all
a users processes:<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>renice 15 -u mikeb<o:p></o:p></b></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908207"></a><a name="_Toc242071392"><span style='mso-bookmark:
_Toc240908207'><span lang=EN-US>1.6 Installation of Software in Linux</span></span></a></h2>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>There
are several different types of installation files for Linux, and few of them
are as easy to install as the EXE installation files found on Windows. For
Linux we find several different types of files: .deb, .rpm, .bin, .tar.gz,
INSTALL, .sh, etc. These different files all have a different method of
execution. Below are instructions on installing these filetypes. The following
section assumes that we are running Ubuntu Linux system.<o:p></o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908208"><span lang=EN-US><o:p>&nbsp;</o:p></span></a></h3>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><span
style='mso-bookmark:_Toc240908208'><a name="_Toc242071393"><span lang=EN-US>1.6.1
Using apt-get</span></a></span></h3>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Ubuntu
has something called <i>apt-get</i>, which allows you to draw from a set of
online repositories (stored in the /etc/apt/sources.list file) that house
packages (i.e., programs/software). The <i>apt-get</i> command does several
things at onceit downloads the appropriate files, downloads all their
dependencies, and installs all of them. A single command installs the software.
You don't have to download a separate installer file or unzip or go through a
wizard or reboot. For example, if I wanted to install Thunderbird, I'd type
these commands in a <a href="http://www.psychocats.net/ubuntu/terminal">terminal</a>:
<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b>sudo apt-get update<br>
</b>$ <b>sudo apt-get install thunderbird<o:p></o:p></b></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The first command looks both at what I
have installed and what's available in the repositories. The second command
downloads the packages needed for Thunderbird and installs them. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Another great thing about <i>apt-get</i>
is the ability to install several different packages at once. For example, if I
wanted to install not only Thunderbird but Firefox, GIMP, Inkscape, Juk, and
Wine, I could type in these commands:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b>sudo apt-get update<br>
</b>$ <b>sudo apt-get install thunderbird firefox gimp inkscape juk wine<o:p></o:p></b></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>And all of those packages would
download and install themselves. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>This is the best way of installing
software in Ubuntu because it automatically resolves all dependencies and
installs them.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:6.0pt;margin-left:0cm'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name=DAPPC-PGFID-946043></a><a name="_Toc240908209"></a><a name="_Toc242071394"><span
style='mso-bookmark:_Toc240908209'><span style='mso-bookmark:DAPPC-PGFID-946043'><span
lang=EN-US>1.6.2 Configuring the sources.list File</span></span></span></a></h3>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The <i>sources.list</i> file resides in
the <i>/etc/apt</i> directory. Like most other Linux configuration files, it
can be revised by using an ordinary text editor, such as </span><kbd><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ae</span></kbd><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>.<o:p></o:p></span></p>

<p class=para style='text-align:justify'><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
file contains a series of lines, each specifying a source for packages. The
lines are consulted serially, so it's usually advantageous to place lines that
specify local sources&nbsp;- such as a CD-ROM&nbsp;- ahead of lines that
specify remote sources. Doing so can save many minutes of download time.<o:p></o:p></span></p>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Each line has the form:<o:p></o:p></span></p>

<pre><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>    </span>deb <em><span
style='font-family:"Courier New"'><o:p></o:p></span></em></span></pre><pre
style='margin-left:28.8pt'><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>uri distribution components</span></em><span
lang=EN-US style='font-size:11.0pt'><o:p></o:p></span></pre>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><code><i><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>uri</span></i></code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> is a
universal resource identifier (URI) the specifies the computer on which the
packages reside, the location of the packages, and the protocol used for
accessing the packages. It has the following form:<o:p></o:p></span></p>

<pre style='margin-left:28.8pt'><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>protocol</span></em><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>://<em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></em></span></pre><pre style='margin-left:
28.8pt'><em><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>host</span></em><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/<em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></em></span></pre><pre style='margin-left:
28.8pt'><em><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>path</span></em><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></pre>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Four protocols&nbsp;- sometimes called
URI types&nbsp;- are recognized:<o:p></o:p></span></p>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='margin-left:32.4pt;border-collapse:collapse;border:none;mso-border-alt:
 solid windowtext .5pt;mso-yfti-tbllook:480;mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
 mso-border-insideh:.5pt solid windowtext;mso-border-insidev:.5pt solid windowtext'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes'>
  <td width=108 valign=top style='width:81.0pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US>cdrom</span></p>
  <p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>
  </td>
  <td width=264 valign=top style='width:198.0pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US>A local CD-ROM drive.</span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1'>
  <td width=108 valign=top style='width:81.0pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US>file&nbsp;</span></p>
  </td>
  <td width=264 valign=top style='width:198.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US>A directory of the local filesystem.</span></p>
  <p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2'>
  <td width=108 valign=top style='width:81.0pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US>http</span></p>
  <p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>
  </td>
  <td width=264 valign=top style='width:198.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US>A Web server.</span></p>
  <p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3;mso-yfti-lastrow:yes'>
  <td width=108 valign=top style='width:81.0pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US>ftp&nbsp;&nbsp;</span></p>
  <p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>
  </td>
  <td width=264 valign=top style='width:198.0pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US>An FTP server.</span></p>
  <p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>
  </td>
 </tr>
</table>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><code><i><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>host</span></i></code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> part
of the URI and the preceding pair of slashes (//) are used only for the <i>http</i>
and <i>ftp</i> protocols. There, the </span><code><i><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>host</span></i></code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> part
of the URI gives the name of the host that contains the packages.<o:p></o:p></span></p>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><code><i><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>path</span></i></code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> part
of the URI always appears, with the preceding slash (/). It specifies the
absolute path of the directory that contains the packages. <o:p></o:p></span></p>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Here are some examples of typical URIs:<o:p></o:p></span></p>

<pre style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>cdrom:/cdrom<o:p></o:p></span></pre><pre
style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>cdrom:/mnt/cdrom<o:p></o:p></span></pre><pre
style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>file:/mnt<o:p></o:p></span></pre><pre
style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>file:/debian<o:p></o:p></span></pre><pre
style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>http://www.us.debian.org/debian<o:p></o:p></span></pre><pre
style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>http://non-us.debian.org/debian-non-US<o:p></o:p></span></pre><pre
style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>ftp://ftp.debian.org/debian<o:p></o:p></span></pre><pre
style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>ftp://nonus.debian.org/debian-non-US</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></pre>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The distribution part of a <i>sources.list</i>
line specifies the distribution release that contains the packages. Typical
values include:<o:p></o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l31 level1 lfo15;tab-stops:list 36.0pt'><b><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>stable</span></b><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> : The latest stable release; that is, one that is
     commonly regarded as having sufficiently few serious bugs for everyday
     use.<o:p></o:p></span></li>
</ul>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l31 level1 lfo15;tab-stops:list 36.0pt'><b><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>unstable</span></b><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'> : The latest unstable release.
     This release sometimes contains serious bugs and should not be installed
     by users who require high levels of system availability or reliability.<o:p></o:p></span></li>
</ul>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The components part of a <i>sources.list</i>
line specifies the parts of the distribution that will be accessed. Typical
values include:<o:p></o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l1 level1 lfo16;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>main: The main set of packages.<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l1 level1 lfo16;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>contrib.: Packages not an integral
     part of the distribution, but which may be useful.<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l1 level1 lfo16;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>non-free: Packages that contain
     software distributed under terms too restrictive to allow inclusion in the
     distribution, but which may be useful.<o:p></o:p></span></li>
</ul>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>A typical <i>sources.list</i> file
might contain the following entries:<o:p></o:p></span></p>

<pre style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>deb file:/cdrom stable main contrib<o:p></o:p></span></pre><pre
style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>deb http://www.us.debian.org/debian stable main contrib non-free<o:p></o:p></span></pre><pre
style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'>deb http://non-us.debian.org/debian-non-US stable non-US</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></pre>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>This configuration allows rapid access
to the distribution packages contained on the local CD-ROM. It also allows
convenient access via the network to other packages and more recent package
versions stored on web servers. <o:p></o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name=DAPPC-PGFID-946131></a><a name="_Toc240908210"></a><a name="_Toc242071395"><span
style='mso-bookmark:_Toc240908210'><span style='mso-bookmark:DAPPC-PGFID-946131'><span
lang=EN-US>1.6.3 Using apt-get</span></span></span></a></h3>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Once you've configured sources.list,
you can use </span><kbd><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>apt-get</span></kbd><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> to update information on available packages, to install a
package, or to upgrade installed packages.<o:p></o:p></span></p>

<h4 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level4 lfo33'><a
name=DAPPC-PGFID-946135><span lang=EN-US>1.6.3.1 Updating Information on
Available Packages</span></a></h4>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To update information on available
packages, issue the following command:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b>sudo apt-get update<o:p></o:p></b></span></p>

<h4 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level4 lfo33'><a
name=DAPPC-PGFID-946141><span lang=EN-US>1.6.3.2 Installing a <span
style='mso-spacerun:yes'> </span>Package</span></a></h4>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To install a specified package, issue
the following command:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo apt-get install
&lt;<em><span style='font-family:"Courier New";font-style:normal'>package&gt;</span></em><o:p></o:p></b></span></p>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>where </span><code><i><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>package</span></i></code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
specifies the name of the package to be installed.<o:p></o:p></span></p>

<h4 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level4 lfo33'><a
name=DAPPC-PGFID-946149><span lang=EN-US>1.6.3.3 Upgrading Installed Packages</span></a></h4>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To automatically upgrade all installed
packages to the latest available version, issue the following command: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo apt-get upgrade <o:p></o:p></b></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h4 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level4 lfo33'><a
name="_Toc240908211"><span lang=EN-US>1.6.7 Installing DEB files</span></a></h4>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>A .deb
file is the easiest file to install on Ubuntu--if you are given an option for
the type of file you want to download, choose this option. Save the file to
your Desktop. Once it is there, simply double click on the file and the system
package installer will open. Click the button in the top right corner that says
&quot;Install Package&quot;, and wait for it to say finished. Close the window.
Your application is now installed and ready to use.<o:p></o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908212"></a><a name="_Toc242071396"><span style='mso-bookmark:
_Toc240908212'><span lang=EN-US>1.6.8 Installing RPM files</span></span></a></h3>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>DEB
files are the default installation file for Ubuntu--if at all possible, you
should choose a .deb file over any other file type. However, sometimes an
application is only available in one or two formats, none of which are
Ubuntu-flavored. RPM is one such file type. In order to install this file, you
will need to convert it into something Ubuntu knows how to install--a .deb
file!<o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To do this, open the Terminal and type:
<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'> </span></span></b><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'>$ s<b>udo apt-get install alien<o:p></o:p></b></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>You will be prompted to enter your
password. After entering, press the return key. You will see some code scroll
by quickly, and then you will be presented with the option to continue or quit
the installation. Type 'Y' and press the return key. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>You will see the Alien application
installing; this app will be used to convert your RPM file into a DEB file.
Installation could take several minutes depending on your Internet and computer
speeds. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Once finished, move the RPM file to
your Desktop and open the Terminal. Type: cd Desktop. This will point your
Terminal to your Desktop directory where you have the RPM file saved.<o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Now, to install the RPM file, in the
Terminal, type: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'> </span></span></b><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'>$ <b>sudo alien -k filename.rpm<o:p></o:p></b></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Replace filename.rpm with the actual
name of the RPM file, then press the return key. It will convert the RPM file
to a DEB file. Once finished, install the DEB file using the method above. <o:p></o:p></span></p>

<h3 style='margin-left:0cm;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908213"></a><a name="_Toc242071397"><span style='mso-bookmark:
_Toc240908213'><span lang=EN-US>1.6.9 Install BIN files</span></span></a></h3>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>A BIN file is similar to an RPM file,
in that Ubuntu can't understand how to install it until you convert it into a
different format. To do this, follow these instructions. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Download and save the BIN file to your
systems Desktop. Once saved, open the Terminal and type: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-spacerun:yes'> </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>$ <b>cd Desktop<o:p></o:p></b></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Once you've cd'ed to the Desktop, type
the following line into the Terminal: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b>sudo chmod +x
filename.bin<o:p></o:p></b></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Change
filename.bin to the name of your BIN file and press the return key. Nothing
will show up in the Terminal, nothing will be copied to the Desktop--it will
appear as if nothing at all happened. This is not the case, however, so do not
worry. Type ./filename.bin and press the return key. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The program will install from within
the Terminal. <o:p></o:p></span></p>

<p><b><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<b><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-font-kerning:16.0pt;mso-ansi-language:EN-US;mso-fareast-language:EN-US;
mso-bidi-language:AR-SA'><br clear=all style='page-break-before:always'>
</span></b>

<h1><a name="_Toc240908214"></a><a name="_Toc242071398"><span style='mso-bookmark:
_Toc240908214'><span lang=EN-US>Chapter 2: Compressing And Archiving Files</span></span></a><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-begin'></span> XE &quot;Compressing
And Archiving Files&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--></h1>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Large files use a lot of disk space and take longer than
smaller files to transfer from one system to another over a network. If you do
not need to look at the contents of a large file very often, you may want to
save it on a CD, DVD, or another medium and remove it from the hard disk. If
you have a continuing need for the file, retrieving a copy from a CD may be
inconvenient. To reduce the amount of disk space you use without removing the
file entirely, you can compress the file without losing any of the information
it holds. Similarly a single archive of several files packed into a larger file
is easier to manipulate, upload, download, and email than multiple files. You
may frequently download compressed, archived files from the Internet. The
utilities described in this section compress and decompress files and pack and
unpack archives.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908215"></a><a name="_Toc242071399"><span style='mso-bookmark:
_Toc240908215'><span lang=EN-US>2.1 Compress A File Using: </span></span></a><span
style='mso-bookmark:_Toc242071399'><span style='mso-bookmark:_Toc240908215'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>bzip2</span></span></span></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bzip2</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> utility
compresses a file by analyzing it and recoding it more efficiently.<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The new version of the file looks completely different. In
fact, because the new file contains many nonprinting characters, you cannot
view it directly. The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>bzip2</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> utility works particularly well on files that contain a lot
of repeated information, such as ext and image data, although most image data
is already in a compressed format. The following example shows a boring file.
Each of the 8,000 lines of the </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>letter_e </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>file contains 72 es and a NEWLINE character that marks the
end of the line. The file occupies more than half a megabyte of disk storage.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-rw-r--<span
style='mso-spacerun:yes'>  </span>1 sam sam 584000 Mar<span
style='mso-spacerun:yes'>  </span>1 <st1:time Minute="31" Hour="22" w:st="on">22:31</st1:time>
letter_e<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The<span style='mso-spacerun:yes'> 
</span></span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>l</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
(long) option causes<span style='mso-spacerun:yes'>  </span>ls to display more
information about a file. Here it shows that letter_e is 584,000 bytes long.
The </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>verbose </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>(or </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>v</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>) option causes </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>bzip2</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> to report how much it was able to reduce the size of the
file. In this case, it shrank the file by 99.99 percent:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>bzip2 -v letter_e<o:p></o:p></b></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>letter_e: 11680.00:1, 0.001
bits/byte, 99.99% saved, 584000 in, 50 out.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-rw-r--<span
style='mso-spacerun:yes'>  </span>1 sam sam 50 Mar<span
style='mso-spacerun:yes'>  </span>1 <st1:time Minute="31" Hour="22" w:st="on">22:31</st1:time>
letter_e.bz2<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Now the file is only 50 bytes long. The </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bzip2</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> utility also
renamed the file, appending </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>.bz2</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> to its name. This naming convention reminds you that the
file is compressed; you would not want to display or print it, for example,
without first decompressing it. The </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>bzip2</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> utility does not change the modification date associated
with the file, even though it completely changes the files contents.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>In the following, more realistic
example, the file<span style='mso-spacerun:yes'>  </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>zach.jpg </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>contains
a computer<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>graphics image:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>  </span>1 sam sam 33287 Mar<span
style='mso-spacerun:yes'>  </span>1 <st1:time Minute="40" Hour="22" w:st="on">22:40</st1:time>
zach.jpg<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bzip2</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> utility can
reduce the size of the file by only 28 percent because the image is already in
a compressed format:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>bzip2 -v zach.jpg</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>zach.jpg:<span
style='mso-spacerun:yes'>  </span>1.391:1,<span style='mso-spacerun:yes'> 
</span>5.749 bits/byte, 28.13% saved, 33287 in, 23922 out.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908216"></a><a name="_Toc242071400"><span style='mso-bookmark:
_Toc240908216'><span lang=EN-US>2.2 Decompress A File Using: </span></span></a><span
style='mso-bookmark:_Toc242071400'><span style='mso-bookmark:_Toc240908216'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>bunzip2</span></span></span></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>You can use the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bunzip2</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
utility to restore a file that has been compressed with </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bzip2</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>bunzip2 letter_e.bz2</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-rw-r--<span
style='mso-spacerun:yes'>  </span>1 sam sam 584000 Mar<span
style='mso-spacerun:yes'>  </span>1 <st1:time Minute="31" Hour="22" w:st="on">22:31</st1:time>
letter_e<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>bunzip2 zach.jpg.bz2</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l<o:p></o:p></b></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>  </span>1 sam sam<span style='mso-spacerun:yes'> 
</span>33287 Mar<span style='mso-spacerun:yes'>  </span>1 <st1:time Minute="40"
Hour="22" w:st="on">22:40</st1:time> zach.jpg<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>This command is similar to </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bzip2 </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>with </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>d </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>option.<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908217"></a><a name="_Toc242071401"><span style='mso-bookmark:
_Toc240908217'><span lang=EN-US>2.3 Compress A File Using: </span></span></a><span
style='mso-bookmark:_Toc242071401'><span style='mso-bookmark:_Toc240908217'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>gzip</span></span></span></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>gzip</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> (GNU zip) utility is older and less efficient than </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bzip2</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>. Its flags and
operations are very similar to those of </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bzip2</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>. A file
compressed by </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>gzip</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> is marked by a </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>.gz
</span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>filename extension. Linux stores manual
pages in </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>gzip</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> format to save disk space; likewise, files you download
from the Internet are frequently in<span style='mso-spacerun:yes'>  </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>gzip</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> format. Use </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>gzip</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> <span
style='mso-spacerun:yes'> </span></span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>and gunzip</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> just as you would use </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bzip2 and bunzip2</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
respectively. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908218"></a><a name="_Toc242071402"><span style='mso-bookmark:
_Toc240908218'><span lang=EN-US>2.4 Archiving Files: </span></span></a><span
style='mso-bookmark:_Toc242071402'><span style='mso-bookmark:_Toc240908218'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>tar</span></span></span><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'><o:p></o:p></span></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>ta</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>r utility performs many functions. Its name is short for
tape archive, as its original function was to create and read archive and
backup tapes. Today it is used to create a single file (called a tar file,
archive, or tarball) from multiple files or directory hierarchies and to
extract files from a tar file.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>.<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>In the following example, the first </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> shows the
existence and sizes of the files </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>g,</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>b</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, and </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>d</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. Next<span style='mso-spacerun:yes'>  </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ta</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>r uses the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>c</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> (create), </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>v</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> (verbose), and </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>f</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> (write to or read
from a file) options to create an archive named </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>all.tar</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> from
these files. Each line output displays the name of the file </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>tar</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> is appending to
the archive it is creating. The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>ta</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>r utility adds overhead when it creates an archive. The next
command shows that the archive file </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>all.tar
</span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>occupies about 9,700 bytes, whereas the
sum of the sizes of the three files is about 6,000 bytes. This overhead is more
appreciable on smaller files, such as the ones in this example.<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l g b d</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>   </span>1 jenny jenny 1302 Aug 20 <st1:time
Minute="16" Hour="14" w:st="on">14:16</st1:time> g<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>   </span>1 jenny other 1178 Aug 20 <st1:time
Minute="16" Hour="14" w:st="on">14:16</st1:time> b<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>   </span>1 jenny jenny 3783 Aug 20 <st1:time
Minute="17" Hour="14" w:st="on">14:17</st1:time> d<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>tar -cvf all.tar g b d</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>g<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>b<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>d<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l all.tar</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>   </span>1 jenny jenny 9728 Aug 20 <st1:time
Minute="17" Hour="14" w:st="on">14:17</st1:time> all.tar<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>tar -tvf all.tar</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r-- jenny/jenny<span
style='mso-spacerun:yes'>    </span>1302 2007-08-20 <st1:time Minute="16"
Hour="14" w:st="on">14:16</st1:time> g<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r-- jenny/other<span
style='mso-spacerun:yes'>    </span>1178 2007-08-20 <st1:time Minute="16"
Hour="14" w:st="on">14:16</st1:time> b<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r-- jenny/jenny<span
style='mso-spacerun:yes'>    </span>3783 2007-08-20 <st1:time Minute="17"
Hour="14" w:st="on">14:17</st1:time> d<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The final command in the preceding example uses the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>t</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> option to display
a table of contents for the archive. Use </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>x</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> instead of </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>t </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>to extract files
from a tar archive. Omit the </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>v</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> option if you want </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>tar</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to do its work
silently.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>You can use </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>bzip2</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, or </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>gzip</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> to compress<span style='mso-spacerun:yes'>  </span>tar
files, making them easier to store and handle. Many files you download from the
Internet will already be in one of these formats. Files that have been
processed by </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>ta</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>r
and compressed by </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>bzip2</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> frequently have a filename extension of<span
style='mso-spacerun:yes'>  </span></span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>.tar.bz2</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> or<span style='mso-spacerun:yes'>  </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>.tbz</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>. Those processed
by<span style='mso-spacerun:yes'>  </span></span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ta</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>r and </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>gzip</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> have an extension
of </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>.tar.gz</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> or </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>.tz</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> extension.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>You can unpack a tarred and gzipped file in two steps.
(Follow the same procedure if the file was compressed by </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bzip2</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>, but use </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bunzip2</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
instead of </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>gunzip</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>.) The next example shows how to unpack the GNU<span
style='mso-spacerun:yes'>  </span>make utility.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l mak*</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-rw-r-- <span
style='mso-spacerun:yes'> </span>1 sam sam 1211924 Jan 20 <st1:time Minute="49"
Hour="11" w:st="on">11:49</st1:time><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>make-3.80.tar.gz<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>gunzip mak*</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l mak</b>*<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-rw-r--<span
style='mso-spacerun:yes'>  </span>1 sam sam 4823040 Jan 20 <st1:time Minute="49"
Hour="11" w:st="on">11:49</st1:time><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>make-3.80.tar<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>tar -xvf mak*</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>make-3.80/<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>make-3.80/po/<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>make-3.80/po/Makefile.in.in<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>...<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>make-3.80/tests/run_make_tests.pl<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>make-3.80/tests/test_driver.pl<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The first command lists the downloaded<span
style='mso-spacerun:yes'>  </span>tarred and<span style='mso-spacerun:yes'> 
</span>gzipped file: </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>make-3.80.tar.gz
</span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>(about 1.2 megabytes). The asterisk (*)
in the filename matches any characters in any filenames, so you end up with a
list of files whose names begin with mak; in this case there is only one. Using
an asterisk saves typing and can improve accuracy with long filenames. The<span
style='mso-spacerun:yes'>  </span></span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>gunzip</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command decompresses the file and yields </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>make-3.80.tar </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>(no </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>.gz </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>extension), which
is about 4.8 megabytes. The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>tar</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command creates the </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>make-3.80 </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>directory
in the working directory and unpacks the files into it.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -ld mak*</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>drwxrwxr-x<span
style='mso-spacerun:yes'>  </span>8 sam sam<span style='mso-spacerun:yes'>   
</span>4096 <st1:date Year="2002" Day="3" Month="10" w:st="on">Oct<span
 style='mso-spacerun:yes'>  </span>3<span style='mso-spacerun:yes'> 
 </span>2002</st1:date> make-3.80<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-rw-r--<span
style='mso-spacerun:yes'>  </span>1 sam sam 4823040 Jan 20 <st1:time Minute="49"
Hour="11" w:st="on">11:49</st1:time> make-3.80.tar<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l make-3.80</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>total 1816<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>  </span>1 sam sam<span style='mso-spacerun:yes'> 
</span>24687 <st1:date Year="2002" Day="3" Month="10" w:st="on">Oct<span
 style='mso-spacerun:yes'>  </span>3<span style='mso-spacerun:yes'> 
 </span>2002</st1:date> ABOUT-NLS<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>  </span>1 sam sam<span style='mso-spacerun:yes'>  
</span>1554 <st1:date Year="2002" Day="8" Month="7" w:st="on">Jul<span
 style='mso-spacerun:yes'>  </span>8<span style='mso-spacerun:yes'> 
 </span>2002</st1:date> AUTHORS<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>  </span>1 sam sam<span style='mso-spacerun:yes'> 
</span>18043 <st1:date Year="1996" Day="10" Month="12" w:st="on">Dec 10<span
 style='mso-spacerun:yes'>  </span>1996</st1:date> COPYING<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>  </span>1 sam sam<span style='mso-spacerun:yes'> 
</span>32922 <st1:date Year="2002" Day="3" Month="10" w:st="on">Oct<span
 style='mso-spacerun:yes'>  </span>3<span style='mso-spacerun:yes'> 
 </span>2002</st1:date> ChangeLog<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>...<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>  </span>1 sam sam<span style='mso-spacerun:yes'> 
</span>16520 <st1:date Year="2000" Day="21" Month="1" w:st="on">Jan 21<span
 style='mso-spacerun:yes'>  </span>2000</st1:date> vmsify.c<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-r--r--<span
style='mso-spacerun:yes'>  </span>1 sam sam<span style='mso-spacerun:yes'> 
</span>16409 <st1:date Year="2002" Day="9" Month="8" w:st="on">Aug<span
 style='mso-spacerun:yes'>  </span>9<span style='mso-spacerun:yes'> 
 </span>2002</st1:date> vpath.c<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>drwxrwxr-x<span
style='mso-spacerun:yes'>  </span>5 sam sam<span style='mso-spacerun:yes'>  
</span>4096 <st1:date Year="2002" Day="3" Month="10" w:st="on">Oct<span
 style='mso-spacerun:yes'>  </span>3<span style='mso-spacerun:yes'> 
 </span>2002</st1:date> w32</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>After </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>tar</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> extracts the files from the archive, the working directory
contains two files whose names start with mak: make-3.80.tar and make-3.80. The
d (directory) option causes </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>ls</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> to display only file and directory names, not the contents
of directories as it normally does. The final </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command shows the
files and directories in the make-3.80 directory.<o:p></o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<b><span lang=EN-US style='font-size:16.0pt;font-family:"Cambria",serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Courier New";
mso-font-kerning:16.0pt;mso-ansi-language:EN-US;mso-fareast-language:EN-US;
mso-bidi-language:AR-SA'><br clear=all style='page-break-before:always'>
</span></b>

<h1><a name="_Toc240908219"></a><a name="_Toc242071403"><span style='mso-bookmark:
_Toc240908219'><span lang=EN-US style='mso-bidi-font-family:"Courier New"'>Chapter
3: </span><span lang=EN-US>Mange File Ownership</span></span></a><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-begin'></span> XE &quot;Mange File
Ownership&quot; </span><![endif]--><!--[if supportFields]><span lang=EN-US><span
style='mso-element:field-end'></span></span><![endif]--></h1>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<h2><a name="_Toc242071404"><span lang=EN-US>3.1 Users and Groups</span></a></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Anyone using a Linux computer is a user. The system keeps
track of different users, by username. Security features allow different users
to have different privileges. Users can belong to groups, allowing security to
be managed for collections of people with different requirements. We use the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>su</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command to switch
to a different user. It is quicker than logging off and back on again. The
command </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>su</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
prompts us for the users password:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>su - bob</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Password:<b
style='mso-bidi-font-weight:normal'><o:p></o:p></b></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The  option makes </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>su</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> behave as if weve
logged in as that user.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071405"><span lang=EN-US>3.2 The Superuser: Root</span></a></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Every Linux system has a user called root. The root user
is all-powerful. It can access any &#64257;les. The root user account should
only be used for system administration, such as installing software. When
logged in as root, the shell prompt usually ends in #. It is usually best to
use </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>su</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
for working as root:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>whoami</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>fred<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>su -<o:p></o:p></b></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Password:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>whoami<o:p></o:p></b></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>root<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071406"><span lang=EN-US>3.3 Changing File Ownership: chown</span></a></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>chown</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command changes
the ownership of &#64257;les or directories. This is a security feature. Only
the superuser can change the ownership of a &#64257;le. Simple usage follows:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>chown bob logfile.txt</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The above command makes </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>log&#64257;le.txt</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to be
owned by the user </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>bob.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>We can specify any number of
&#64257;les or directories as arguments in the command.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071407"><span lang=EN-US>3.4 Changing File Ownership: </span></a><span
style='mso-bookmark:_Toc242071407'><span lang=EN-US style='mso-bidi-font-family:
"Courier New"'>chgrp</span></span></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The chgrp command changes the group
ownership of &#64257;les or directories. Simple usage follows:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>chgrp staff report.txt<o:p></o:p></b></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The above command makes </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>staff</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> be the group
owner of the &#64257;le </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>log&#64257;le.txt</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>As for </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>chown,</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> we can specify any number of &#64257;les or directories.
The superuser can change the group ownership of any &#64257;le to any group.
The owner of a &#64257;le can also change its group ownership. But only to a
group of which the owner is a member<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071408"><span lang=EN-US>3.5 Changing the Ownership of a Directory
and Its Contents</span></a></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>A common requirement is to change the
ownership of a directory and its contents. Both </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>chown</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> and </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>chgrp</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> accept a -R
(Mnemonic: recursive) option:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'> </span># <b style='mso-bidi-font-weight:normal'>chgrp
-R staff shared-directory</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The above command changes the group
ownership of </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>shared-directory </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>and<span style='mso-spacerun:yes'>  </span>its contents and
its subdirectories, recursively to </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>staff.
</span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Changing user ownership (superuser
only):<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'> </span></span><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'># <b>chown -R root /usr/local/share/misc/</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071409"><span lang=EN-US>3.6 Manage File Permission to
Control Access to Files</span></a></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>A permission represents an action that
can be done on the file. There are three types of permissions to a file; each
denoted by a letter:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='margin-left:41.4pt;border-collapse:collapse;border:none;mso-border-alt:
 solid windowtext .5pt;mso-yfti-tbllook:480;mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
 mso-border-insideh:.5pt solid windowtext;mso-border-insidev:.5pt solid windowtext'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes'>
  <td width=87 valign=top style='width:64.95pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Permission<o:p></o:p></span></p>
  </td>
  <td width=59 valign=top style='width:44.4pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Letter <o:p></o:p></span></p>
  </td>
  <td width=310 valign=top style='width:232.65pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Description<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1'>
  <td width=87 valign=top style='width:64.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Read<o:p></o:p></span></p>
  </td>
  <td width=59 valign=top style='width:44.4pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Courier New"'>r<o:p></o:p></span></p>
  </td>
  <td width=310 valign=top style='width:232.65pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Permission to read the data stored in
  the &#64257;le<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2'>
  <td width=87 valign=top style='width:64.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Write <o:p></o:p></span></p>
  </td>
  <td width=59 valign=top style='width:44.4pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Courier New"'>w<o:p></o:p></span></p>
  </td>
  <td width=310 valign=top style='width:232.65pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Permission to write new data to the
  &#64257;le, to truncate<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>the &#64257;le, or to overwrite
  existing data<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3;mso-yfti-lastrow:yes'>
  <td width=87 valign=top style='width:64.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Execute <o:p></o:p></span></p>
  </td>
  <td width=59 valign=top style='width:44.4pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Courier New"'>x<o:p></o:p></span></p>
  </td>
  <td width=310 valign=top style='width:232.65pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Permission to attempt to execute the
  contents of the<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>&#64257;le as a program<o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>r,w,x</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><span
style='mso-spacerun:yes'>  </span>permissions also have a meaning for
directories:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='margin-left:41.4pt;border-collapse:collapse;border:none;mso-border-alt:
 solid windowtext .5pt;mso-yfti-tbllook:480;mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
 mso-border-insideh:.5pt solid windowtext;mso-border-insidev:.5pt solid windowtext'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes'>
  <td width=87 valign=top style='width:64.95pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Permission<o:p></o:p></span></p>
  </td>
  <td width=59 valign=top style='width:44.35pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Letter<o:p></o:p></span></p>
  </td>
  <td width=310 valign=top style='width:232.7pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Description<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1'>
  <td width=87 valign=top style='width:64.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Read<o:p></o:p></span></p>
  </td>
  <td width=59 valign=top style='width:44.35pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Courier New"'>r<o:p></o:p></span></p>
  </td>
  <td width=310 valign=top style='width:232.7pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Permission to get a listing of the
  directory<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2'>
  <td width=87 valign=top style='width:64.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Write<o:p></o:p></span></p>
  </td>
  <td width=59 valign=top style='width:44.35pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Courier New"'>w<o:p></o:p></span></p>
  </td>
  <td width=310 valign=top style='width:232.7pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Permission to create, delete, or
  rename &#64257;les (or<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>subdirectories) within the directory<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3;mso-yfti-lastrow:yes'>
  <td width=87 valign=top style='width:64.95pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Execute<o:p></o:p></span></p>
  </td>
  <td width=59 valign=top style='width:44.35pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Courier New"'>x<o:p></o:p></span></p>
  </td>
  <td width=310 valign=top style='width:232.7pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Permission to change to the
  directory, or to use the<o:p></o:p></span></p>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>directory as an intermediate part of
  a path to a &#64257;le<o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>As well as having different types of permission, we can
apply different sets of permissions to different sets of people. A &#64257;le
(or directory) has an owner and a group owner. The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>r,w,x</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> permissions are
speci&#64257;ed separately for the owner, for the group owner, and for everyone
else (the world).<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071410"><span lang=EN-US>3.7 Examining Permission of a
file: </span></a><span style='mso-bookmark:_Toc242071410'><span lang=EN-US
style='mso-bidi-font-family:"Courier New"'>ls l</span></span></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ls -l</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command allows us
to look at the permissions on a &#64257;le:<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l<o:p></o:p></b></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>drwxr-x--- 9 aaronc staff
4096 Oct 12 <st1:time Minute="57" Hour="12" w:st="on">12:57</st1:time> accounts<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>-rw-rw-r-- 1 aaronc staff
11170 Dec 9 <st1:time Minute="11" Hour="14" w:st="on">14:11</st1:time>
report.txt<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The third and fourth columns are the
owner and group-owner. The &#64257;rst column specify the permissions: <o:p></o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l9 level1 lfo5;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>one character for the &#64257;le
     type: </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>d</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> for directories,<span style='mso-spacerun:yes'> 
     </span> for plain &#64257;les. <o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l9 level1 lfo5;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>three characters of </span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>rwx</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> permissions for the owner (or a dash if the permission
     isnt available)<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l9 level1 lfo5;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>three characters of </span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>rwx</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> <span style='mso-spacerun:yes'> </span>permissions for
     the group owner<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l9 level1 lfo5;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>three characters of </span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>rwx</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> permissions for everyone else<o:p></o:p></span></li>
</ul>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>If someone owns a &#64257;le, then </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>per-owner permissions</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
apply to him. Otherwise, if he is in the group that group-owns the &#64257;le,
then </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>per-group permissions</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> apply to him. If neither of those is the case, </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>then for-everyone-else permissions</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> apply to him.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071411"><span lang=EN-US>3.8 Changing Permissions of Files
and Directories: </span></a><span style='mso-bookmark:_Toc242071411'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>chmod</span></span></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>chmod</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command changes the permissions of a &#64257;le or
directory. A &#64257;les permissions may be changed only by its owner or by
the superuser. The command </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>chmod</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> takes an argument describing the new permissions. The
permissions can be speci&#64257;ed in many &#64258;exible (but correspondingly
complex) ways. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Permissions can be set using letters in
the following format:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>[ugoa][+=-][rwx]<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l19 level1 lfo6;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>The &#64257;rst letters indicate
     who to set permissions for: </span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>u</span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'> for the &#64257;les owner, </span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>g</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> for the group owner, </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Courier New"'>o</span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
     for other users, or </span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>a</span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'> for all users<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l19 level1 lfo6;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>= </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>sets permissions for &#64257;les, </span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>+</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> adds permissions to those already set, and </span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'></span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> removes permissions<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l19 level1 lfo6;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>The &#64257;nal letters indicate
     which of the </span><span lang=EN-US style='font-size:11.0pt;font-family:
     "Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>r,w,x</span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'><span style='mso-spacerun:yes'> 
     </span>permissions to set<o:p></o:p></span></li>
</ul>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>For example if we want to add
executable permission for a program named </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>bubblesort</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to
all users, we type the following command:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>$<span style='mso-spacerun:yes'>  </span></span><b
style='mso-bidi-font-weight:normal'><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>chmod a+x bubblesort<o:p></o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>We may use numerical permissions with </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>chmod. </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Three
decimal numbers identify permissions for owner, group and others. The number in
binary format should be interpreted as follows:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:28.8pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-tab-count:1'>   </span>Decimal: <span
style='mso-tab-count:1'> </span>664<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:28.8pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-tab-count:1'>   </span>Bianry:<span
style='mso-tab-count:2'>     </span>110 110 100<span style='mso-tab-count:1'> </span><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:28.8pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-tab-count:1'>   </span>Meaning:<span
style='mso-tab-count:1'> </span>rwx rwx rwx<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Explanation:<span style='mso-spacerun:yes'>    </span>A 1
in each position specifies permission, a 0 specifies no permission.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>For example:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>chmod 664 bubblesort</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The above command is equivalent to:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>chmod ug=rw,o=r bubblesort</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>A common requirement is to change the
permissions of a directory and its contents. The command </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>chmod</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> accepts a R
(Mnemonic: recursive) option:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>chmod -R g+rwX,o+rX public-directory</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The above command <o:p></o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l18 level1 lfo7;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>Adds </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Courier New"'>rwx</span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
     permissions on </span><span lang=EN-US style='font-size:11.0pt;font-family:
     "Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>public-directory</span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'> for the group owner, and adds </span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>rx</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'> permissions on it for everyone else<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l18 level1 lfo7;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>And any subdirectories,
     recursively<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l18 level1 lfo7;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>Any any contained executable
     &#64257;les<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l18 level1 lfo7;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>Contained non-executable
     &#64257;les have </span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>rw</span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'> permissions added for the group
     owner, and </span><span lang=EN-US style='font-size:11.0pt;font-family:
     "Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>r</span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'> permission for everyone else<o:p></o:p></span></li>
</ul>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071412"><span lang=EN-US>3.9 Special Directory Permissions:
Sticky</span></a></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/tmp</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> directory must be world-writable, so that anyone may create
temporary &#64257;les within it. But that would normally mean that anyone may
delete any &#64257;les within it  obviously a security hole. A directory may
have sticky permissions: Only a &#64257;les owner may delete it from a
sticky directory. Expressed with a t (mnemonic: temporary directory) in a
listing:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l -d /tmp</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>drwxrwxrwt 30 root root
11264 Dec 21 <st1:time Minute="35" Hour="9" w:st="on">09:35</st1:time> /tmp<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>We<span style='mso-spacerun:yes'> 
</span>enable sticky permission with the following command:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>#<span style='mso-spacerun:yes'>  </span></span><b
style='mso-bidi-font-weight:normal'><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>chmod +t /data/tmp</span></b><b style='mso-bidi-font-weight:
normal'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p></o:p></span></b></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<h2><a name="_Toc242071413"><span lang=EN-US>3.10 Special Directory
Permissions: Setgid</span></a></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>If a directory is </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>setgid</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> (set group-id), &#64257;les created within it acquire the
group ownership of the directory and directories created within it acquire both
the group ownership and </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>setgid</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> permission. It is useful for a shared directory where all
users working on its &#64257;les are in a given group. It is expressed with an
s in group position in a listing:<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>ls -l -d /data/projects</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>drwxrwsr-x 16 root staff
4096 Oct 19 <st1:time Minute="14" Hour="13" w:st="on">13:14</st1:time>
data/projects<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>We enable setgid with:<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>chmod g+s /data/projects<o:p></o:p></b></span></p>

<p class=MsoNormal><b style='mso-bidi-font-weight:normal'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<h1><a name="_Toc240908220"></a><a name="_Toc242071414"><span style='mso-bookmark:
_Toc240908220'><span lang=EN-US>Chapter 4: FileSystem: Mouning and Unmouning</span></span></a><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-begin'></span> XE &quot;FileSystem\:
Mouning and Unmouning&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--></h1>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>A filesystem in this context is a hierarchy of directories
that is located on a single partition (logically independent section of a hard
disk drive) or other <i>device</i>, such as a CDROM, DVD, floppy disk or USB
key drive, and has a single <i>filesystem type</i> (i.e., method for organizing
data).<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>As far as many parts of a Linux system are concerned, a
partition contains entirely arbitrary data. When installing, we set things up
so that a partition contains a &#64257;lesystem  a way of organising data into
&#64257;les and directories. One &#64257;lesystem is made the root
&#64257;lesystem: the root directory on that &#64257;lesystem becomes the
directory named /. Other &#64257;lesystems can be mounted: the root directory
of that &#64257;lesystem is grafted onto a<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>directory of the root &#64257;lesystem.
This arranges for every &#64257;le in every mounted &#64257;lesystem to be
accessible from a single uni&#64257;ed name space. The directory grafted onto
is called the mount point.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071415"><span lang=EN-US>4.1 Mounting filesystem: </span></a><span
style='mso-bookmark:_Toc242071415'><span lang=EN-US style='mso-bidi-font-family:
"Courier New"'>mount</span></span></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman";mso-bidi-font-style:italic'>Mounting</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> refers to logically attaching a filesystem to a specified
location on the currently accessible (and thus already mounted) filesystem(s)
on a computer system so that its contents can be accessed by users. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Important &#64257;lesystems are mounted at boot-up; other
&#64257;lesystems can be mounted or unmounted at any time. The </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>mount</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> command mounts a
&#64257;lesystem. We usually need to have root permission to mount a
&#64257;lesystem. The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>mount</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command makes it easy to <st1:place w:st="on"><st1:PlaceType
 w:st="on">mount</st1:PlaceType> <st1:PlaceName w:st="on">&#64257;lesystems</st1:PlaceName></st1:place>
con&#64257;gured by the system administrator. For example, many systems are
con&#64257;gured so that the following command:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>mount /mnt/cdrom<o:p></o:p></b></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>will mount the contents of the
machines CD-ROM drive under the directory </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/mnt/cdrom<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>mount /dev/sdb3 /mnt/extra </b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The above command mounts the
&#64257;lesystem stored in the </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/dev/sdb3</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> device on the<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>mount point </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/mnt/extra. We</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> may
occasionally need to specify the &#64257;lesystem type explicitly: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>mount -t vfat /dev/hdd1 /mnt/windows<o:p></o:p></b></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Allowable &#64257;lesystem types are
listed in the </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>mount(8) manpage. </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>To see a list of the &#64257;lesystems currently mounted,
run </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>mount</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> without any options.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/fstab</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> &#64257;le contains information about &#64257;lesystems
that are known to the system administrator. Specifying a &#64257;lesystem in </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/fstab</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> makes
it possible to use its mount point as the only argument to </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>mount</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>. /</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>etc/fstab</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> also
con&#64257;gures which &#64257;lesystems should be mounted at boot-up Each line
in </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/fstab</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> describes one &#64257;lesystem. There are six columns on
each line.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Sample </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/fstab is shown below:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='margin-left:23.4pt;border-collapse:collapse;border:none;mso-border-alt:
 solid windowtext .5pt;mso-yfti-tbllook:480;mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
 mso-border-insideh:.5pt solid windowtext;mso-border-insidev:.5pt solid windowtext'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes'>
  <td width=61 valign=top style='width:45.65pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Device<o:p></o:p></span></p>
  </td>
  <td width=102 valign=top style='width:76.65pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Mount-point<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Type<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Options<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Dump<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Pass-no<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1'>
  <td width=61 valign=top style='width:45.65pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/dev/hda3<o:p></o:p></span></p>
  </td>
  <td width=102 valign=top style='width:76.65pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Ext2<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Defaults<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>1<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>1<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2'>
  <td width=61 valign=top style='width:45.65pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/dev/hda1<o:p></o:p></span></p>
  </td>
  <td width=102 valign=top style='width:76.65pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/bot<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Ext2<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Defauls <o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>1<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>2<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3'>
  <td width=61 valign=top style='width:45.65pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/dev/hda5<o:p></o:p></span></p>
  </td>
  <td width=102 valign=top style='width:76.65pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/usr<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Ext2<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Defaults<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>1<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>2`<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:4'>
  <td width=61 valign=top style='width:45.65pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/dev/hdb1<o:p></o:p></span></p>
  </td>
  <td width=102 valign=top style='width:76.65pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/usr/local<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Ext2<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Defaults<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>1<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>2<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:5'>
  <td width=61 valign=top style='width:45.65pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/dev/hdb2<o:p></o:p></span></p>
  </td>
  <td width=102 valign=top style='width:76.65pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/home<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Ext2<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Defaults<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>1<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>2<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:6'>
  <td width=61 valign=top style='width:45.65pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/dev/scd0<o:p></o:p></span></p>
  </td>
  <td width=102 valign=top style='width:76.65pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/mnt/cdrom<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Iso9660<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Noauto, users,ro<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>0<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>0<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:7;mso-yfti-lastrow:yes'>
  <td width=61 valign=top style='width:45.65pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/dev/fd0<o:p></o:p></span></p>
  </td>
  <td width=102 valign=top style='width:76.65pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>/mnt/floppy<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Auto<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>Noauto, users<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>0<o:p></o:p></span></p>
  </td>
  <td width=84 valign=top style='width:63.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>0<o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The most common &#64257;lesystem types
are:<o:p></o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l4 level1 lfo8;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>ext2</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>  The standard Linux &#64257;lesystem<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l4 level1 lfo8;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>iso9660  The &#64257;lesystem
     used on CD-ROMs<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l4 level1 lfo8;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>proc</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>  Not a real &#64257;lesystem, so uses none as the
     device. Used as a way for the kernel to report system information to user
     processes<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l4 level1 lfo8;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>vfa</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>t  The &#64257;lesystem used by Windows 95<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l4 level1 lfo8;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>auto</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>  Not a real &#64257;lesystem type. Used as a way of
     asking the mount command to probe for various &#64257;lesystem types,
     particularly for removable media<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l4 level1 lfo8;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>Networked &#64257;lesystems
     include </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>nf</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>s (Unix-speci&#64257;c) and </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Courier New"'>smbfs</span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
     (Windows or Samba)<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l4 level1 lfo8;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>Other, less common types exist;
     see </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>mount(8)</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'><o:p></o:p></span></li>
</ul>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>There are comma-separated options in <span
style='mso-spacerun:yes'> </span></span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/fstab</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. Alternatively, use comma-separated options with </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>-o</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> on the mount
command line. Common </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>mount </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>options:<o:p></o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l30 level1 lfo9;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>Noauto</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>  In </span><span lang=EN-US style='font-size:11.0pt;
     font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/fstab</span><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>, prevents the &#64257;lesystem
     being mounted at bootup. Useful for removable media<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l30 level1 lfo9;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>ro</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>  Mount the &#64257;lesystem read-only<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l30 level1 lfo9;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>users</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>  Let non-root users mount and unmount this
     &#64257;lesystem<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l30 level1 lfo9;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>user</span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>  Like users, but non-root users can only unmount
     &#64257;lesystems that they themselves mounted<o:p></o:p></span></li>
</ul>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Other less common mount options exist,
as well as many options for individual &#64257;lesystem types  see mount(8).<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The &#64257;fth column is called </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>dump</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>. It is used by
the </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>dump</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> and </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>restore</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> backup utilities. Few people use those tools. We just use 1
for normal &#64257;lesystems, and 0 for removable &#64257;lesystems.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The sixth column is called </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>pass-no. </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>This controls
the order in which automatically-mounted &#64257;lesystems are checked by </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>fsck.</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>We use 1 for the
root &#64257;lesystem and 0 for &#64257;lesystems that arent mounted at
boot-up. We use 2 for other &#64257;lesystems.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071416"><span lang=EN-US>4.2 Unmounting Filesystem: umount</span></a></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Unmounting refers to logically detaching a filesystem from
the currently accessible filesystem(s). All mounted filesystems are unmounted
automatically when a computer is shut down in an orderly manner. However, there
are times when it is necessary to unmount an individual filesystem while a
computer is still running. A common example is when it is desired to remove an
external device such as a USB key drive; should such device be removed before
the filesystem on it is properly unmounted, it is possible that any data
recently added to it might not be saved. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The basic syntax of </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>umount</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> is:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>umount [options] filesystem<o:p></o:p></b></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>umount</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> is
most commonly used without any of its several options. The filesystem is
identified by the full pathname of the directory in which it has been mounted,
not by its type. Thus, for example, to unmount a filesystem that is mounted in
a directory called /dir1, all that would be necessary is to type in the
following at the keyboard and press the Enter key: <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>umount /dir1 <o:p></o:p></b></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Likewise, a USB key device, assuming
that it had been mounted in the directory </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/mnt/usb</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>,
would be unmounted with the following: <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>umount /mnt/usb</b> <o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Attempts to unmount a filesystem are not always successful.
The most common problem is that the filesystem is busy. That is, it is
currently being used by some process (i.e., instance of a program in
execution). In such case an error message such as </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>umount: /dir1: device is busy</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> will be displayed on the screen. This busy state could be
the result of something as simple as an GUI window being open that shows an
icon of the directory containing the filesystem, in which case it can be easily
solved by closing the window. Or it could be the result of a file on that
filesystem being open, in which case all that is necessary is to close the
file. In less obvious cases, it may be necessary to use a command such as </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ps</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> or </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>pstree</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to
try to locate the offending process(es) and then use a command such as kill to
terminate such process(es).<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Another cause of failure is when a user attempts to unmount
a filesystem that has already been unmounted. In such case an error message
such as </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>umount: /dir1: not mounted</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> will be returned. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>In the event that the unmounting is successful, </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>umoun</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>t usually works
silently; that is, there is no message on the screen to confirm its success. However,
</span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>umount </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>can be made to provide such a message by using the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>-v </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>(i.e., verbose)
option. (This should not be confused with the </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>-V </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>option, which
merely returns information about the currently installed version of </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>umoun</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>t.)<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>umoun</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>t allows the name
of the physical device on which the filesystem is mounted to be included in the
command if desired. This is convenient because it can minimize typing by
allowing the user to utilize the upward pointing arrow on the keyboard to
display the command that was previously used to mount that filesystem (i.e., to
use the history command) and then merely insert the letter u before the word
mount and press the Enter key in order to unmount the filesystem. Thus, for
example, if a filesystem that is physically located on the second partition of
the first HDD (which is designated by dev/hda2) is mounted in a directory
called /dir2, it can be unmounted with either of the following: <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>umount /dir2</b> <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>or <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>umount /dev/hda2 /dir2</b> <o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Interestingly, when the physical device
is included, a confirmation message is automatically supplied. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>There are several options that can be tried in the event
that </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>umount</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> refuses to unmount a filesystem for no immediately apparent
reason. Perhaps the most useful is the -l (i.e., lazy) option, which immediately
detaches the filesystem from the main filesystem and then cleans up all
references to the unmounted filesystem as soon as it is no longer busy. This
capability requires Linux kernel 2.4.11 or later. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Another way to deal with an unmounting failure is to use the
-r option, which remounts the filesystem as read-only. This presumably allows
devices or media to be removed without affecting data which has just been
written to them. In addition, the </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>-f </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>option forces unmounting in the case of an unreachable NFS
(network filesystem) filesystem. <o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The -a option causes all of the filesystems described in </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/mtab </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>to be
unmounted. (However, with </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>umount</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> version 2.7 and later the </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>proc</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> filesystem is not
unmounted.) </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/mtab</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> is a file that is similar to </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/fstab </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>and
which is updated by </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>mount</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> and </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>umoun</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>t whenever filesystems are mounted or unmounted. The -n
option causes unmounting to occur without writing to </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/mtab</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>-t </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>option followed by the filesystem type indicates that the
actions should only be taken on filesystems of that type. Multiple types can be
specified in a comma-separated list. This list can be prefixed with the word no
to specify filesystem types on which no action should be taken. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>-O</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> options indicate that the actions should only be taken on
filesystems with the specified options in </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/fstab</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>.
Multiple option types can be specified in a comma-separated list. Those options
for which no action should be taken can be prefixed with no. <o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>umount</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> will
free any loop device associated with a mounted filesystem if it finds the
option </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>loop=...</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> in </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/mtab </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>or if the </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>-d </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>option is used. A loop device is a pseudo-device that is
able to redirect and transform data that goes through its loop and which is
used mainly used for encrypting filesystems. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Note the symmetry between the </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>umount</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> and </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>moun</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>t commands,
including the fact that many of the options are identical or very similar
(including </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>-a, -h, -r, -t, -O, -v and -V</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>). This is consistent with the Unix philosophy, a
fundamental component of which is simplicity (and hence consistency to the
extent practical among commands), in that it eliminates unnecessary complexity.
<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>umount</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> could
have instead been called unmount. This might have simplified things for people
who are new to the command line (i.e., text-only operation). However,
eliminating unnecessary typing is also a part of the Unix philosophy, and thus
the n was not used. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<b><span lang=EN-US style='font-size:16.0pt;font-family:"Cambria",serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-font-kerning:16.0pt;mso-ansi-language:EN-US;mso-fareast-language:EN-US;
mso-bidi-language:AR-SA'><br clear=all style='page-break-before:always'>
</span></b>

<h1><a name="_Toc240908221"></a><a name="_Toc242071417"><span style='mso-bookmark:
_Toc240908221'><span lang=EN-US>Chapter 5: Managing User Accounts</span></span></a><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-begin'></span> XE &quot;Managing User
Accounts&quot; </span><![endif]--><!--[if supportFields]><span lang=EN-US><span
style='mso-element:field-end'></span></span><![endif]--></h1>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<h2><a name="_Toc242071418"><span lang=EN-US>5.1 What is an Account?</span></a></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>When a computer is used by many people it is usually
necessary to differentiate between the users, for example, so that their
private files can be kept private. This is important even if the computer can
only be use by a single person at a time, as with most microcomputers. Thus,
each user is given a unique username, and that name is used to log in. There's
more to a user than just a name, however. An account is all the files,
resources, and information belonging to one user. The term hints at banks, and
in a commercial system each account usually has some money attached to it, and
that money vanishes at different speeds depending on how much the user stresses
the system. For example, disk space might have a price per megabyte and day,
and processing time might have a price per second<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<h2><a name="_Toc242071419"><span lang=EN-US>5.2 Creating User Account: </span></a><span
style='mso-bookmark:_Toc242071419'><span lang=EN-US style='mso-bidi-font-family:
"Courier New"'>adduser</span></span></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To create a user account, you use the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>adduser</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
command, which has the form:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>adduser userid</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>where </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>userid</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
specifies the name of the user account that you want to create. The command
prompts you for the information needed to create the account.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Here's a typical example of using the
command, which creates a user account named </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>newbie</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>adduser newbie</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Adding user newbie...<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Adding new group newbie
(1001).<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Adding new user newbie
(1001) with group newbie.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Creating home directory
/home/newbie.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Copying files from /etc/skel<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Changing password for newbie<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Enter the new password
(minimum of 5, maximum of 8 characters)<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Please use a combination of
upper and lower case letters and numbers.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Re-enter new password:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Password changed.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Changing the user
information for newbie<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Enter the new value, or
press return for the default<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:21.6pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>  </span>Full Name []: Newbie Dewbie<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:21.6pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>  </span>Room Number []:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:21.6pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>  </span>Work Phone []:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:21.6pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>  </span>Home Phone []:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:21.6pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>  </span>Other []:<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Is the information correct?
[y/n] <o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>y<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>#<o:p></o:p></span></p>

<p class=para style='text-align:justify'><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Notice
that the lines where the password was typed were overwritten by the subsequent
lines. Moreover, for security, passwords are not echoed to the console as they
are typed. Notice also that several of the information fields were
omitted&nbsp;- for example, Room Number. You can specify such information if
you think it may be useful, but the system makes no use of the information and
doesn't require you to provide it. The similarly named </span><kbd><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>useradd</span></kbd><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
command also creates a user account, but does not prompt you for the password
or other information. <o:p></o:p></span></p>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071420"><span lang=EN-US>5.3 Changing <span
style='mso-spacerun:yes'> </span>a Users name: </span></a><span
style='mso-bookmark:_Toc242071420'><span lang=EN-US style='mso-bidi-font-family:
"Courier New"'>chfn</span></span></h2>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>You can change the name associated with
a user account, by using the </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>chfn</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><span style='mso-tab-count:4'>            </span><span
style='mso-tab-count:1'>   </span>#<span style='mso-spacerun:yes'>  </span></span><b
style='mso-bidi-font-weight:normal'><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'>chfn -f</span></b><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'> <span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'> </span><b style='mso-bidi-font-weight:normal'>name
userid</b></span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>where </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>name</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> specifies the new name and </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>userid</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
specifies the account to be modified. If the name contains spaces or other
special characters, it should be enclosed in double quotes (&quot;). For
example, to change the name associated with the account newbie to Dewbie
Newbie, you would enter the following command:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>chfn -f &quot;Dewbie Newbie&quot; newbie</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908222"></a><a name="_Toc242071421"><span style='mso-bookmark:
_Toc240908222'><span lang=EN-US>5.4 Changing a User Accounts Password: </span></span></a><span
style='mso-bookmark:_Toc242071421'><span style='mso-bookmark:_Toc240908222'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>passwd</span></span></span><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'><o:p></o:p></span></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>From time to time, you should change your password, making
it more difficult for others to break into your system. As system
administrator, you may sometimes need to change the password associated with a
user's account. For instance, some users have a bad habit of forgetting their
password. They'll come to you, the system administrator, seeking help in
accessing their account.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To change a password, you use the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>passwd</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
command. To change your own password, enter a command like this one:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>passwd<o:p></o:p></b></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>This command changes the password associated with the
current user account. You don't have to be logged in as root to change a
password. Because of this, users can change their own passwords without the
help of the system administrator. The root user, however, can change the
password associated with any user account, as you'll see shortly. Of course,
only root can do so - other users can change only their own password.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The passwd command initiates a simple
dialog that resembles the following:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b style='mso-bidi-font-weight:
normal'>passwd</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Changing password for newbie<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Old password:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Enter the new password
(minimum of 5, maximum of 8 characters)<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Please use a combination of
upper and lower case letters and numbers.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>New password:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Re-enter new password:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Password changed.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Notice the restrictions governing the choice of password,
which are designed to prohibit passwords that might be easily guessed. If you
choose a password that violates these restrictions, the command will refuse the
password, prompting you for another.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>As the root user, you can change the password associated
with any user account. The system doesn't ask you for the current password, it
immediately prompts for the new password:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>passwd newbie</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Changing password for newbie<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Enter the new password
(minimum of 5, maximum of 8 characters)<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Please use a combination of
upper and lower case letters and numbers.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>New password:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Re-enter new password:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>Password changed.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Information on users is stored in the file </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/passwd</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>,
which you can view using a text editor. Any user can read this file, though
only the root user can modify it. If you selected shadow passwords, passwords
are encrypted and stored in the file /</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>etc/shadow</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, which can be read only by the root user.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908223"></a><a name="_Toc242071422"><span style='mso-bookmark:
_Toc240908223'><span lang=EN-US>5.5 Configuring Group Definitions</span></span></a></h2>

<p class=para style='text-align:justify'><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Linux
uses groups to define a set of related user accounts that can share access to a
file or directory. You probably won't often find it necessary to configure
group definitions, particularly if you use your system as a desktop system
rather than a server. However, when you wish, you create and delete groups and
modify their membership lists. <o:p></o:p></span></p>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908224"></a><a name="_Toc242071423"><span style='mso-bookmark:
_Toc240908224'><span lang=EN-US>5.6 Creating a Group: </span></span></a><span
style='mso-bookmark:_Toc242071423'><span style='mso-bookmark:_Toc240908224'><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'>groupadd</span></span></span><span
lang=EN-US style='mso-bidi-font-family:"Courier New"'><o:p></o:p></span></h2>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To create a new group, use the </span><kbd><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>groupadd</span></kbd><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
command:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-tab-count:1'>   </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'># <b
style='mso-bidi-font-weight:normal'>groupadd <em><span style='font-family:"Courier New";
font-style:normal;mso-bidi-font-style:italic'>group</span></em></b><i
style='mso-bidi-font-style:normal'><o:p></o:p></i></span></p>

<p class=para style='text-align:justify'><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>where
</span><code><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New";mso-bidi-font-style:italic'>group</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> specifies the name of the group to be added. Groups are
stored in the file </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New";mso-bidi-font-style:
italic'>/etc/group</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>,</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> which can be read by any user but modified only by </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>root</span></code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>.<o:p></o:p></span></p>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>For example, to add a group named </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>newbies</span></code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>,</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> you would enter the following command:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-tab-count:1'>   </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'># <b
style='mso-bidi-font-weight:normal'>groupadd newbies<o:p></o:p></b></span></p>

<pre><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<h2><a name="_Toc240908225"></a><a name="_Toc242071424"><span style='mso-bookmark:
_Toc240908225'><span lang=EN-US>5.7 Deleting a Group</span></span></a></h2>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To delete a group, user the </span><kbd><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>groupdel</span></kbd><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
command:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-tab-count:1'>   </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'># <b
style='mso-bidi-font-weight:normal'>groupdel <em><span style='font-family:"Courier New";
font-style:normal;mso-bidi-font-style:italic'>group</span></em></b><o:p></o:p></span></p>

<p class=para style='text-align:justify'><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>where
</span><code><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New";mso-bidi-font-style:italic'>group</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> specifies the name of the group to be deleted. For example,
to delete the group named </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>newbies</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>,</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> you would enter
the following command:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-tab-count:1'>   </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'># <b
style='mso-bidi-font-weight:normal'>groupdel newbies</b><o:p></o:p></span></p>

<p class=para><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908226"></a><a name="_Toc242071425"><span style='mso-bookmark:
_Toc240908226'><span lang=EN-US>5.8 Adding a member to a group</span></span></a></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To add a member to a group, you use a
special form of the </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>adduser</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> command:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-spacerun:yes'>   </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'># <b
style='mso-bidi-font-weight:normal'>adduser user group</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>where user specifies the member and group specifies the
group to which the member is added. For example, to add the user </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>newbie01</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to
the group </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>newbies</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, you would enter the following command:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-spacerun:yes'>  </span></span><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'># <b
style='mso-bidi-font-weight:normal'>adduser newbie01 newbies</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908227"></a><a name="_Toc242071426"><span style='mso-bookmark:
_Toc240908227'><span lang=EN-US>5.9 Removing a member from a group</span></span></a></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Unfortunately, no command removes a user from a specified
group. The easiest way to remove a member from a group is by editing the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/group</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> file.
Here's an excerpt from a typical </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/grou</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>p file:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>users:x:100:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>nogroup:x:65534:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>bmccarty:x:1000:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>newbies:x:1002:newbie01,newbie02,newbie03<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Each line in the file describes a
single group and has the same form as other lines, consisting of a series of
fields separated by colons (:). The fields are:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<ul style='margin-top:0cm' type=disc>
 <li class=MsoNormal style='mso-list:l32 level1 lfo14;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>Group name </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'><span style='mso-spacerun:yes'> </span>:<span
     style='mso-spacerun:yes'>  </span><span style='mso-spacerun:yes'> </span>The
     name of the group.<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l32 level1 lfo14;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>Password </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>: <span style='mso-spacerun:yes'> </span>The encrypted
     password associated with the group. This field is not generally used,
     containing an x instead.<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l32 level1 lfo14;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>Group ID </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'><span style='mso-spacerun:yes'> </span>: <span
     style='mso-spacerun:yes'> </span>The unique numeric ID associated with the
     group. <o:p></o:p></span></li>
 <li class=MsoNormal style='mso-list:l32 level1 lfo14;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Courier New"'>Member list </span><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'><span style='mso-spacerun:yes'> </span>: <span
     style='mso-spacerun:yes'> </span>A list of user accounts, with a comma (,)
     separating each user account from the next. <o:p></o:p></span></li>
</ul>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To remove a member from a group, first
create a backup copy of the </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/group</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># cp /etc/group
/etc/group.SAVE<o:p></o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The backup can prove helpful if you modify the file
incorrectly. Next, open the </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/group</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file in a text editor. Locate the line that describes the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>group</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> and delete the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>user name</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> and
the following comma, if any. Save the file, exit the editor, and check your
work.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908228"></a><a name="_Toc242071427"><span style='mso-bookmark:
_Toc240908228'><span lang=EN-US>5.10 Deleting a User Account</span></span></a></h2>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To delete a user account, use the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>userde</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>l command:<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>userdel user</b><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>where </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>use</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>r specifies the
account to be deleted. If you want to delete the user's home directory, its
files and subdirectories, use this form of the command:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'># <b style='mso-bidi-font-weight:
normal'>userdel -r user</b><o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<b><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-font-kerning:16.0pt;mso-ansi-language:EN-US;mso-fareast-language:EN-US;
mso-bidi-language:AR-SA'><br clear=all style='page-break-before:always'>
</span></b>

<h1><a name="_Toc240908229"></a><a name="_Toc242071428"><span style='mso-bookmark:
_Toc240908229'><span lang=EN-US style='mso-bidi-font-size:11.0pt'>Chapter 6: </span><span
lang=EN-US>Samba File Server</span></span></a></h1>

<h1><!--[if supportFields]><span lang=EN-US><span style='mso-element:field-begin'></span><span
style='mso-spacerun:yes'> </span>XE &quot;Samba File Server&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--><span
lang=EN-US style='mso-bidi-font-size:11.0pt'><o:p></o:p></span></h1>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>One of the most common ways to network
Ubuntu and Windows computers is to configure Samba as a File Server. This
section covers setting up a <b>Samba</b> server to share files with Windows
clients. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The server will be configured to share files with any client
on the network without prompting for a password.<span
style='mso-spacerun:yes'>   </span><o:p></o:p></span></p>

<h2><a name="_Toc240908230"></a><a name="_Toc242071429"><span style='mso-bookmark:
_Toc240908230'><span lang=EN-US>6.1 Installation</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The first step is to install the <b>samba</b> package. From
a terminal prompt enter: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'> </span></span></b><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'>$<b> sudo apt-get install samba</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>That's all there is to it; you are now ready to configure
Samba to share files. <o:p></o:p></span></p>

<h2><a name="_Toc240908231"></a><a name="_Toc242071430"><span style='mso-bookmark:
_Toc240908231'><span lang=EN-US>6.2 Configuration</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The main Samba configuration file is
located in </span><span lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/etc/samba/smb.conf</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. The default configuration file has a significant amount of
comments in order to document various configuration directives (Not all the
available options are included in the default configuration file. See the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>smb.conf</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> <b>man</b>
page). <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>First, edit the following key/value pairs in the <i>[global]</i>
section of </span><span lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>etc/samba/smb.conf</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>   </span>workgroup = EXAMPLE<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>   </span>...<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>   </span>security = user<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The <i>security</i> parameter is farther down in the
[global] section, and is commented by default. Also, change <i>EXAMPLE</i> to
better match your environment. <o:p></o:p></span></p>

<ol start=1 type=1>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l13 level1 lfo17;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>Create a new section at the bottom of the file, or
     uncomment one of the examples, for the directory to be shared: <o:p></o:p></span></li>
</ol>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>[share]<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>    </span>comment = Ubuntu File Server Share<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'> </span><span style='mso-spacerun:yes'>   </span>path
= /srv/samba/share<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>    </span>browsable = yes<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>    </span>guest ok = yes<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>    </span>read only = no<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-spacerun:yes'>    </span>create mask = 0755<o:p></o:p></span></p>

<ol start=1 type=1>
 <ul type=disc>
  <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:
      auto;mso-list:l13 level2 lfo17;tab-stops:list 72.0pt'><i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'>comment:</span></i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'> a short description of the
      share. Adjust to fit your needs. <o:p></o:p></span></li>
  <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:
      auto;mso-list:l13 level2 lfo17;tab-stops:list 72.0pt'><i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'>path:</span></i><span lang=EN-US
      style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
      "Times New Roman"'> the path to the directory to share. <o:p></o:p></span></li>
 </ul>
</ol>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
margin-left:72.0pt;text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>This
example uses </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/srv/samba/sharename</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> because, according to the <i>Filesystem Hierarchy Standard
(FHS)</i>, <u><span style='color:blue'>/srv</span></u> is where site-specific
data should be served. Technically Samba shares can be placed anywhere on the
filesystem as long as the permissions are correct, but adhering to standards is
recommended. <o:p></o:p></span></p>

<ol start=1 type=1>
 <ul type=disc>
  <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:
      auto;mso-list:l13 level2 lfo17;tab-stops:list 72.0pt'><i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'>browsable:</span></i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'> enables Windows clients to
      browse the shared directory using <b>Windows Explorer</b>. <o:p></o:p></span></li>
  <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:
      auto;mso-list:l13 level2 lfo17;tab-stops:list 72.0pt'><i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'>guest ok:</span></i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'> allows clients to connect to the
      share without supplying a password. <o:p></o:p></span></li>
  <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:
      auto;mso-list:l13 level2 lfo17;tab-stops:list 72.0pt'><i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'>read only:</span></i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'> gives write access to the shared
      directory. <o:p></o:p></span></li>
  <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:
      auto;mso-list:l13 level2 lfo17;tab-stops:list 72.0pt'><i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'>create mask:</span></i><span
      lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
      mso-bidi-font-family:"Times New Roman"'> determines the permissions new
      files will have when created. <o:p></o:p></span></li>
 </ul>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     text-align:justify;mso-list:l13 level1 lfo17;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>Now that <b>Samba</b> is
     configured, the directory needs to be created and the permissions changed.
     From a terminal enter: <o:p></o:p></span></li>
</ol>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo mkdir -p
/srv/samba/share</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo chown
nobody.nogroup /srv/samba/share/<o:p></o:p></b></span></p>

<p class=MsoNormal style='margin-left:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The <i>-p</i> switch tells mkdir to create the entire
directory tree if it doesn't exist. Change the share name to fit your
environment.</span><span lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<ol start=3 type=1>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l13 level1 lfo17;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>Finally, restart the <b>samba</b> services to enable
     the new configuration: <o:p></o:p></span></li>
</ol>

<p class=MsoNormal style='margin-left:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo
/etc/init.d/samba restart<o:p></o:p></b></span></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Once again, the above configuration gives all access to any
client on the local network.<span style='mso-spacerun:yes'>   </span></span><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:18.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>From a Windows client you should now be
able to browse to the Ubuntu file server and see the shared directory. To check
that everything is working try creating a directory from Windows. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To create additional shares simply
create new <i>[dir]</i> sections in </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'>/etc/samba/smb.conf</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, and restart <i>Samba</i>. Just make sure that the
directory you want to share actually exists and the permissions are correct. <o:p></o:p></span></p>

<span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA'><br
clear=all style='mso-special-character:line-break;page-break-before:always'>
</span>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908232"></a><a name="_Toc242071431"><span style='mso-bookmark:
_Toc240908232'><span lang=EN-US>6.3 Securing a Samba File and Print Server</span></span></a></h2>

<p class=MsoNormal><b><span lang=EN-US><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><a name="_Toc240908233"><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif'>Samba Security Modes</span></b></a><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>There
are two security levels available to the Common Internet Filesystem (CIFS)
network protocol <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>user-level</span></em> and <em><span style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>share-level</span></em>.
Samba's <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>security mode</span></em> implementation allows more
flexibility, providing four ways of implementing user-level security and one
way to implement share-level: <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l16 level1 lfo18;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>security
= user:</span></em><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'> requires clients to supply a username
and password to connect to shares. Samba user accounts are separate from system
accounts, but the <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>libpam-smbpass</span></strong> package
will sync system users and passwords with the Samba user database. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l16 level1 lfo18;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>security
= domain:</span></em><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'> this mode allows the Samba server to
appear to Windows clients as a Primary Domain Controller (PDC), Backup Domain
Controller (BDC), or a Domain Member Server (DMS).<span
style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l16 level1 lfo18;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>security
= ADS:</span></em><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'> allows the Samba server to join an
Active Directory domain as a native member.<span style='mso-spacerun:yes'> 
</span><o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l16 level1 lfo18;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>security
= server:</span></em><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'> this mode is left over from before
Samba could become a member server, and due to some security issues should not
be used. See the Server Security section of the Samba guide for more details. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l16 level1 lfo18;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>security
= share:</span></em><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'> allows clients to connect to shares
without supplying a username and password. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The security mode you choose will
depend on your environment and what you need the Samba server to accomplish. <o:p></o:p></span></p>

<p class=MsoNormal><a name="_Toc240908234"><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif'>Security = User</span></b></a><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US><span style='mso-spacerun:yes'> </span></span></p>

<p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>First, install the </span><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>libpam-smbpass</span></strong><span lang=EN-US
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
package which will sync the system users to the Samba user database: <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo apt-get
install libpam-smbpass<o:p></o:p></span></strong></p>

<pre><strong><span lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></strong></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>If you chose the <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>Samba Server</span></em> task during installation <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>libpam-smbpass</span></strong> is already installed.<o:p></o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Edit </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/samba/smb.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, and in the <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>[share]</span></em> section change: <o:p></o:p></span></p>

<pre><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><span style='mso-spacerun:yes'>    </span>guest ok = no<o:p></o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Finally, restart Samba for the new
settings to take effect: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/samba restart</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Now when connecting to the shared
directories or printers you should be prompted for a username and password. <o:p></o:p></span></p>

<p class=MsoNormal><a name="_Toc240908235"><span lang=EN-US style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>If you choose to
map a network drive to the share you can check the Reconnect at Logon check
box, which will require you to only enter the username and password once, at
least until the password changes.<o:p></o:p></span></a></p>

<p class=MsoNormal><span style='mso-bookmark:_Toc240908235'><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'>Share
Security</span></b></span><b><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>There
are several options available to increase the security for each individual
shared directory. Using the <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>[share]</span></em> example, this
section will cover some common options. <o:p></o:p></span></p>

<p class=MsoNormal><a name="_Toc240908236"><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif'>Groups</span></b></a><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Groups
define a collection of computers or users which have a common level of access
to particular network resources and offer a level of granularity in controlling
access to such resources. For example, if a group <span class=italic>qa</span>
is defined and contains the users <span class=italic>freda</span>, <span
class=italic>danika</span>, and <span class=italic>rob</span> and a second
group <span class=italic>support</span> is defined and consists of users <span
class=italic>danika</span>, <span class=italic>jeremy</span>, and <span
class=italic>vincent</span> then certain network resources configured to allow
access by the <span class=italic>qa</span> group will subsequently enable
access by freda, danika, and rob, but not jeremy or vincent. Since the user <span
class=italic>danika</span> belongs to both the <span class=italic>qa</span> and
<span class=italic>support</span> groups, she will be able to access resources
configured for access by both groups, whereas all other users will have only
access to resources explicitly allowing the group they are part of. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>By default Samba looks for the local
system groups defined in </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/group</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> to determine which users belong to which groups.<o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>When
defining groups in the Samba configuration file, </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/samba/smb.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, the recognized syntax is to preface the group name with an
&quot;@&quot; symbol. For example, if you wished to define a group named <span
class=italic>sysadmin</span> in a certain section of the </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/samba/smb.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, you would do so by entering the group name as <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>@sysadmin</span></strong>.
<o:p></o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Arial",sans-serif'>File Permissions<o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>File
Permissions define the explicit rights a computer or user has to a particular
directory, file, or set of files. Such permissions may be defined by editing
the </span><code><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/samba/smb.conf</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file and specifying the explicit permissions of a defined
file share. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>For
example, if you have defined a Samba share called <em><span style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>share</span></em>
and wish to give <span class=italic>read-only</span> permissions to the group
of users known as <span class=italic>qa</span>, but wanted to allow writing to
the share by the group called <span class=italic>sysadmin</span> and the user
named <span class=italic>vincent</span>, then you could edit the </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/samba/smb.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file, and add the following entries under the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>[share]</span></em>
entry: <o:p></o:p></span></p>

<pre style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>   </span>read list = @qa<o:p></o:p></span></pre><pre
style='margin-left:28.8pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>   </span>write list = @sysadmin, vincent</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Another
possible Samba permission is to declare <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>administrative</span></em> permissions
to a particular shared resource. Users having administrative permissions may
read, write, or modify any information contained in the resource the user has
been given explicit administrative permissions to. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>For
example, if you wanted to give the user <span class=italic>melissa</span>
administrative permissions to the <span class=italic>share</span> example, you
would edit the </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/samba/smb.conf</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file, and add the following line under the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>[share]</span></em>
entry: <o:p></o:p></span></p>

<pre><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><span style='mso-spacerun:yes'>    </span><span
style='mso-tab-count:1'>               </span></span><span lang=EN-US
style='font-size:11.0pt'>admin users = melissa<o:p></o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>After editing </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/samba/smb.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, restart Samba for the changes to take effect: <o:p></o:p></span></p>

<pre style='text-indent:43.2pt'><strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo /etc/init.d/samba restart<o:p></o:p></span></strong></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>For the <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>read list</span></em> and <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>write list</span></em> to work the Samba security mode must <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>not</span></em> be set to <span
class=italic>security = share</span><o:p></o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Now
that Samba has been configured to limit which groups have access to the shared
directory, the filesystem permissions need to be updated. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Traditional
Linux file permissions do not map well to Windows NT Access Control Lists
(ACLs). Fortunately POSIX ACLs are available on Ubuntu servers providing more
fine grained control. For example, to enable ACLs on </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/srv</span></code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> an
EXT3 filesystem, edit </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/fstab</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> adding the <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>acl</span></em> option: <o:p></o:p></span></p>

<pre><span lang=EN-US style='font-size:11.0pt'>UUID=66bcdd2e-8861-4fb0-b7e4-e61c569fe17d /srv<span style='mso-spacerun:yes'>  </span>ext3<span style='mso-spacerun:yes'>    </span>noatime,relatime,acl 0<span style='mso-spacerun:yes'>       </span>1<o:p></o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Then remount the partition: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo mount -v -o
remount /srv<o:p></o:p></span></strong></p>

<pre><span lang=EN-US style='font-size:11.0pt'><o:p>&nbsp;</o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
above example assumes </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/srv</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> on a separate partition. If </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/srv</span></code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>, or
wherever you have configured your share path, is part of the </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/</span></code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
partition a reboot may be required.<o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>To
match the Samba configuration above the <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>sysadmin</span></em> group will be
given read, write, and execute permissions to </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/srv/samba/share</span></code><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>,
the <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>qa</span></em> group will be given read and execute
permissions, and the files will be owned by the username <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>melissa</span></em>.
Enter the following in a terminal: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo chown -R
melissa /srv/samba/share/</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo chgrp -R
sysadmin /srv/samba/share/</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo setfacl -R
-m g:qa:rx /srv/samba/share/<o:p></o:p></span></strong></p>

<pre><strong><span lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></strong></pre><pre
style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>The <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>setfacl</span></strong> command above gives <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>execute</span></em> permissions to all files in the <code><span
style='mso-ansi-font-size:11.0pt;mso-bidi-font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/srv/samba/share</span></code> directory, which you may or may not want.</span><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><o:p></o:p></span></strong></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Now
from a Windows client you should notice the new file permissions are implemented.
See the <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>acl</span></strong> and <strong><span style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>setfacl</span></strong>
man pages for more information on POSIX ACLs. <o:p></o:p></span></p>

<pre><span lang=EN-US style='font-size:11.0pt'><o:p>&nbsp;</o:p></span></pre>

<p class=MsoNormal><a name="_Toc240908237"><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif'>Samba AppArmor Profile</span></b></a><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Ubuntu
comes with the <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>AppArmor</span></strong> security
module, which provides mandatory access controls. The default AppArmor profile
for Samba will need to be adapted to your configuration. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>There
are default AppArmor profiles for </span><code><span lang=EN-US
style='font-size:11.0pt'>/usr/sbin/smbd</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> and </span><code><span lang=EN-US style='font-size:11.0pt'>/usr/sbin/nmbd</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>, the Samba daemon binaries, as part of the <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>apparmor-profiles</span></strong>
packages. To install the package, from a terminal prompt enter: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo apt-get
install apparmor-profiles</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>By
default the profiles for <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>smbd</span></strong> and <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>nmbd</span></strong>
are in <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>complain</span></em> mode allowing Samba to work without
modifying the profile, and only logging errors. To place the <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>smbd</span></strong>
profile into <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>enforce</span></em> mode, and have Samba work as expected,
the profile will need to be modified to reflect any directories that are
shared. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Edit </span><code><span lang=EN-US
style='font-size:11.0pt'>/etc/apparmor.d/usr.sbin.smbd</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> adding information for <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>[share]</span></em> from the file
server example: <o:p></o:p></span></p>

<pre><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>  </span>/srv/samba/share/ r,<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>  </span>/srv/samba/share/** rwkix,<o:p></o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Now place the profile into <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>enforce</span></em>
and reload it: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo aa-enforce
/usr/sbin/smbd</span></strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> cat
/etc/apparmor.d/usr.sbin.smbd | sudo apparmor_parser -r</span></strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>You
should now be able to read, write, and execute files in the shared directory as
normal, and the <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>smbd</span></strong> binary will have
access to only the configured files and direcotories. Be sure to add entries
for each directory you configure Samba to share. Also, any errors will be
logged to </span><code><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/var/log/syslog</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<b><span lang=EN-US style='font-size:16.0pt;font-family:"Cambria",serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-font-kerning:16.0pt;mso-ansi-language:EN-US;mso-fareast-language:EN-US;
mso-bidi-language:AR-SA'><br clear=all style='page-break-before:always'>
</span></b>

<h1><a name="_Toc240908238"></a><a name="_Toc242071432"><span style='mso-bookmark:
_Toc240908238'><span lang=EN-US>Chapter 7: Network File System (NFS)</span></span></a></h1>

<h1><!--[if supportFields]><span lang=EN-US><span style='mso-element:field-begin'></span><span
style='mso-spacerun:yes'> </span>XE &quot;Network File System (NFS)&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--></h1>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>NFS allows a system to share
directories and files with others over a network. By using NFS, users and
programs can access files on remote systems almost as if they were local files.
<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Some of the most notable benefits that NFS can provide are: <o:p></o:p></span></p>

<ul type=disc>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     text-align:justify;mso-list:l10 level1 lfo19;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>Local workstations use less disk
     space because commonly used data can be stored on a single machine and
     still remain accessible to others over the network.<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l10 level1 lfo19;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>There is no need for users to have separate home
     directories on every network machine. Home directories could be set up on
     the NFS server and made available throughout the network.<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     text-align:justify;mso-list:l10 level1 lfo19;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>Storage devices such as floppy
     disks, CDROM drives, and USB Thumb drives can be used by other machines on
     the network. This may reduce the number of removable media drives
     throughout the network.<o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
margin-left:18.0pt'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908239"></a><a name="_Toc242071433"><span style='mso-bookmark:
_Toc240908239'><span lang=EN-US>7.1 Installation</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>At a terminal prompt enter the following command to install
the NFS Server: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo apt-get install
nfs-kernel-server<o:p></o:p></b></span></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908240"></a><a name="_Toc242071434"><span style='mso-bookmark:
_Toc240908240'><span lang=EN-US>7.2 Configuration</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>You can configure the directories to be exported by adding
them to the </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/exports</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file. For example: <o:p></o:p></span></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/ubuntu<span
style='mso-spacerun:yes'>  </span>*(ro,sync,no_root_squash)<o:p></o:p></span></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/home<span
style='mso-spacerun:yes'>    </span>*(rw,sync,no_root_squash)<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>You can replace * with one of the
hostname formats. Make the hostname declaration as specific as possible so
unwanted systems cannot access the NFS mount. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>To start the NFS server, you can run the following command
at a terminal prompt: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo
/etc/init.d/nfs-kernel-server start</b><o:p></o:p></span></p>

<h2><a name="_Toc240908241"></a><a name="_Toc242071435"><span style='mso-bookmark:
_Toc240908241'><span lang=EN-US>7.3 NFS Client Configuration</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Use the <b>mount</b> command to mount a shared NFS directory
from another machine, by typing a command line similar to the following at a
terminal prompt: <o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo mount
example.hostname.com:/ubuntu /local/Ubuntu<o:p></o:p></b></span></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The mount point directory </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/local/ubuntu</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> must
exist. There should be no files or subdirectories in the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/local/ubuntu</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
directory.</span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>An alternate way to mount an NFS share
from another machine is to add a line to the </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/fstab</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> file.
The line must state the hostname of the NFS server, the directory on the server
being exported, and the directory on the local machine where the NFS share is
to be mounted. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The general syntax for the line in </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/fstab</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> file
is as follows: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:28.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>example.hostname.com:/ubuntu
/local/ubuntu nfs rsize=8192,wsize=8192,timeo=14,intr<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>If you have trouble mounting an NFS
share, make sure the <b>nfs-common</b> package is installed on your client. To
install <b>nfs-common</b> enter the following command at the terminal prompt: <o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo apt-get
install nfs-common</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
mso-outline-level:3'><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><span
style='mso-spacerun:yes'> </span><o:p></o:p></span></b></p>

<span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA'><br
clear=all style='mso-special-character:line-break;page-break-before:always'>
</span>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc240908242"></a><a name="_Toc242071436"><span style='mso-bookmark:
_Toc240908242'><span lang=EN-US>Chapter 8: FTP Server</span></span></a></h1>

<h1><!--[if supportFields]><span lang=EN-US><span style='mso-element:field-begin'></span><span
style='mso-spacerun:yes'> </span>XE &quot;FTP Server&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--></h1>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>File Transfer Protocol (FTP) is a TCP
protocol for uploading and downloading files between computers. FTP works on a
client/server model. The server component is called an <i>FTP daemon</i>. It
continuously listens for FTP requests from remote clients. When a request is
received, it manages the login and sets up the connection. For the duration of
the session it executes any of commands sent by the FTP client. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Access to an FTP server can be managed in two ways:<o:p></o:p></span></p>

<ul type=disc>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l14 level1 lfo20;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>Anonymous<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l14 level1 lfo20;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>Authenticated<o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>In the Anonymous mode, remote clients
can access the FTP server by using the default user account called
&quot;anonymous&quot; or &quot;ftp&quot; and sending an email address as the
password. In the Authenticated mode a user must have an account and a password.
User access to the FTP server directories and files is dependent on the
permissions defined for the account used at login. As a general rule, the FTP
daemon will hide the root directory of the FTP server and change it to the FTP
Home directory. This hides the rest of the file system from remote sessions. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908243"></a><a name="_Toc242071437"><span style='mso-bookmark:
_Toc240908243'><span lang=EN-US>8.1 vsftpd - FTP Server Installation</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>vsftpd is an FTP daemon available in Ubuntu. It is easy to
install, set up, and maintain. To install <b>vsftpd</b> you can run the
following command: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo apt-get install
vsftpd<o:p></o:p></b></span></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908244"></a><a name="_Toc242071438"><span style='mso-bookmark:
_Toc240908244'><span lang=EN-US>8.2 Anonymous FTP Configuration</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>By default <b>vsftpd</b> is configured
to only allow anonymous download. During installation a <i>ftp</i> user is
created with a home directory of </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/home/ftp</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. This is the default FTP directory. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>If you wish to change this location, to
</span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/srv/ftp</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> for example, simply create a directory in another location
and change the <i>ftp</i> user's home directory: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo mkdir /srv/ftp</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo usermod -d
/srv/ftp ftp</b> <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>After making the change restart <b>vsftpd</b>: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo /etc/init.d/vsftpd
restart</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Finally, copy any files and directories you would like to
make available through anonymous FTP to </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/srv/ftp</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908245"></a><a name="_Toc242071439"><span style='mso-bookmark:
_Toc240908245'><span lang=EN-US>8.3 User Authenticated FTP Configuration</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>To configure <b>vsftpd</b> to authenticate system users and
allow them to upload files edit </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/vsftpd.conf</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>local_enable=YES<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>write_enable=YES</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Now restart <b>vsftpd</b>: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><span style='mso-tab-count:1'>   </span></span></b><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo
/etc/init.d/vsftpd restart</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Now when system users login to FTP they
will start in their <i>home</i> directories where they can download, upload,
create directories, etc. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Similarly, by default, the anonymous
users are not allowed to upload files to FTP server. To change this setting,
you should uncomment the following line, and restart <b>vsftpd</b>: <o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>anon_upload_enable=YES<o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Enabling anonymous FTP upload can be an extreme security
risk. It is best to not enable anonymous upload on servers accessed directly
from the Internet.</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The configuration file consists of many
configuration parameters. The information about each parameter is available in
the configuration file. Alternatively, you can refer to the man page, <b>man 5
vsftpd.conf</b> for details of each parameter. <o:p></o:p></span></p>

<h2><a name="_Toc240908246"></a><a name="_Toc242071440"><span style='mso-bookmark:
_Toc240908246'><span lang=EN-US>8.4 Securing FTP</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>There are options in </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/vsftpd.conf</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> to
help make <b>vsftpd</b> more secure. For example users can be limited to their
home directories by uncommenting: <o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>chroot_local_user=YES<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>You can also limit a specific list of users to just their
home directories: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>chroot_list_enable=YES<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>chroot_list_file=/etc/vsftpd.chroot_list<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>After uncommenting the above options, create a </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/vsftpd.chroot_list</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
containing a list of users one per line. Then restart <b>vsftpd</b>: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo /etc/init.d/vsftpd
restart</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Also, the </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/ftpusers</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> file
is a list of users that are <i>disallowed</i> FTP access. The default list
includes root, daemon, nobody, etc. To disable FTP access for additional users
simply add them to the list. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>FTP can also be encrypted using <i>FTPS</i>.
Different from <i>SFTP</i>, <i>FTPS</i> is FTP over Secure Socket Layer (SSL). <i>SFTP</i>
is a FTP like session over an encrypted <i>SSH</i> connection. A major
difference is that users of SFTP need to have a <i>shell</i> account on the
system, instead of a <i>nologin</i> shell. Providing all users with a shell may
not be ideal for some environments, such as a shared web host. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>To configure <i>FTPS</i>, edit </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/vsftpd.conf</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> and
at the bottom add: <o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>ssl_enable=Yes<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Also, notice the certificate and key related options: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>rsa_cert_file=/etc/ssl/certs/ssl-cert-snakeoil.pem<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>rsa_private_key_file=/etc/ssl/private/ssl-cert-snakeoil.key</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>By default these options are set the
the certificate and key provided by the <b>ssl-cert</b> package. In a
production environment these should be replaced with a certificate and key
generated for the specific host.<span style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Now restart <b>vsftpd</b>, and non-anonymous users will be
forced to use <i>FTPS</i>: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo /etc/init.d/vsftpd
restart</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To allow users with a shell of </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/usr/sbin/nologin</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
access to FTP, but have no shell access, edit </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/shells</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
adding the <i>nologin</i> shell: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'># </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Courier New"'>/etc/shells: valid login shells<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/bin/csh<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/bin/sh<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/usr/bin/es<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/usr/bin/ksh<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/bin/ksh<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/usr/bin/rc<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/usr/bin/tcsh<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/bin/tcsh<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/usr/bin/esh<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/bin/dash<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/bin/bash<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/bin/rbash<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/usr/bin/screen<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>/usr/sbin/nologin<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>This is necessary because, by default <b>vsftpd</b>
uses PAM for authentication, and the </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/pam.d/vsftpd</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> configuration file contains: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:4.6pt;text-indent:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>auth<span
style='mso-spacerun:yes'>    </span>required<span
style='mso-spacerun:yes'>        </span>pam_shells.so<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The <i>shells</i> PAM module restricts access to shells
listed in the </span><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/shells</span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Most popular FTP clients can be
configured connect using FTPS. The <b>lftp</b> command line FTP client has the
ability to use FTPS as well. <o:p></o:p></span></p>

<span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA'><br
clear=all style='mso-special-character:line-break;page-break-before:always'>
</span>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc240908247"></a><a name="_Toc242071441"><span style='mso-bookmark:
_Toc240908247'><span lang=EN-US>Chapter 9: Dynamic Host Configuration Protocol
(DHCP)</span></span></a><!--[if supportFields]><span lang=EN-US><span
style='mso-element:field-begin'></span> XE &quot;Dynamic Host Configuration
Protocol (DHCP)&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--></h1>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The Dynamic Host Configuration Protocol
(DHCP) is a network service that enables host computers to be automatically
assigned settings from a server as opposed to manually configuring each network
host. Computers configured to be DHCP clients have no control over the settings
they receive from the DHCP server, and the configuration is transparent to the
computer's user. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The most common settings provided by a DHCP server to DHCP
clients include: <o:p></o:p></span></p>

<ul type=disc>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l22 level1 lfo21;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>IP-Address and Netmask<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l22 level1 lfo21;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>DNS<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l22 level1 lfo21;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>WINS<o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>However, a DHCP server can also supply configuration
properties such as: <o:p></o:p></span></p>

<ul type=disc>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l11 level1 lfo22;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>Host Name<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l11 level1 lfo22;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>Domain Name<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l11 level1 lfo22;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>Default Gateway<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l11 level1 lfo22;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>Time Server<o:p></o:p></span></li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l11 level1 lfo22;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>Print Server<o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The advantage of using DHCP is that
changes to the network, for example a change in the address of the DNS server,
need only be changed at the DHCP server, and all network hosts will be
reconfigured the next time their DHCP clients poll the DHCP server. As an added
advantage, it is also easier to integrate new computers into the network, as
there is no need to check for the availability of an IP address. Conflicts in
IP address allocation are also reduced. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>A DHCP server can provide configuration settings using two
methods: <o:p></o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>MAC Address <o:p></o:p></span></b></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
margin-left:36.0pt;text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>This
method entails using DHCP to identify the unique hardware address of each
network card connected to the network and then continually supplying a constant
configuration each time the DHCP client makes a request to the DHCP server
using that network device. <o:p></o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Address Pool <o:p></o:p></span></b></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
margin-left:36.0pt;text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>This
method entails defining a pool (sometimes also called a range or scope) of IP
addresses from which DHCP clients are supplied their configuration properties
dynamically and on a &quot;first come, first served&quot; basis. When a DHCP
client is no longer on the network for a specified period, the configuration is
expired and released back to the address pool for use by other DHCP Clients. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Ubuntu is shipped with both DHCP server
and client. The server is <b>dhcpd</b> (dynamic host configuration protocol
daemon). The client provided with Ubuntu is <b>dhclient</b> and should be
installed on all computers required to be automatically configured. Both
programs are easy to install and configure and will be automatically started at
system boot. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908248"></a><a name="_Toc242071442"><span style='mso-bookmark:
_Toc240908248'><span lang=EN-US>9.1 Installation</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>At a terminal prompt, enter the following command to install
<b>dhcpd</b>: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo apt-get install
dhcp3-server</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>You will probably need to change the default configuration
by editing /etc/dhcp3/dhcpd.conf to suit your needs and particular
configuration. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>You also need to edit /etc/default/dhcp3-server to specify
the interfaces dhcpd should listen to. By default it listens to eth0. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>NOTE: dhcpd's messages are being sent to syslog. Look there
for diagnostics messages. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908249"></a><a name="_Toc242071443"><span style='mso-bookmark:
_Toc240908249'><span lang=EN-US>9.2 Configuration</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The error message the installation ends with might be a
little confusing, but the following steps will help you configure the service: <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Most commonly, what you want to do is assign an IP address
randomly. This can be done with settings as follows: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'># </span><span lang=EN-US style='font-size:11.0pt;font-family:
"Courier New"'>Sample /etc/dhcpd.conf</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'># (</span><span lang=EN-US style='font-size:11.0pt;font-family:
"Courier New"'>add your comments here) <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>default-lease-time
600;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>max-lease-time
7200;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>option
subnet-mask 255.255.255.0;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>option
broadcast-address 192.168.1.255;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>option routers
192.168.1.254;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>option
domain-name-servers 192.168.1.1, 192.168.1.2;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>option
domain-name &quot;mydomain.example&quot;;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>subnet
192.168.1.0 netmask 255.255.255.0 {<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>range
192.168.1.10 192.168.1.100;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>range
192.168.1.150 192.168.1.200;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:43.2pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>} <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>This will result in the DHCP server
giving a client an IP address from the range 192.168.1.10-192.168.1.100 or
192.168.1.150-192.168.1.200. It will lease an IP address for 600 seconds if the
client doesn't ask for a specific time frame. Otherwise the maximum (allowed)
lease will be 7200 seconds. The server will also &quot;advise&quot; the client
that it should use 255.255.255.0 as its subnet mask, 192.168.1.255 as its
broadcast address, 192.168.1.254 as the router/gateway and 192.168.1.1 and
192.168.1.2 as its DNS servers. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>If you need to specify a WINS server for your Windows
clients, you will need to include the netbios-name-servers option, e.g. <o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:45.8pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>option
netbios-name-servers 192.168.1.1; <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA'><br
clear=all style='mso-special-character:line-break;page-break-before:always'>
</span>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc240908250"></a><a name="_Toc242071444"><span style='mso-bookmark:
_Toc240908250'><span lang=EN-US>Chapter 10: Squid - Proxy Server</span></span></a></h1>

<h1><!--[if supportFields]><span lang=EN-US><span style='mso-element:field-begin'></span><span
style='mso-spacerun:yes'> </span>XE &quot;Squid - Proxy Server&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--></h1>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Squid is a full-featured web proxy
cache server application which provides proxy and cache services for Hyper Text
Transport Protocol (HTTP), File Transfer Protocol (FTP), and other popular
network protocols. Squid can implement caching and proxying of Secure Sockets
Layer (SSL) requests and caching of Domain Name Server (DNS) lookups, and
perform transparent caching. Squid also supports a wide variety of caching
protocols, such as Internet Cache Protocol, (ICP) the Hyper Text Caching
Protocol, (HTCP) the Cache Array Routing Protocol (CARP), and the Web Cache
Coordination Protocol. (WCCP) <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The Squid proxy cache server is an
excellent solution to a variety of proxy and caching server needs, and scales
from the branch office to enterprise level networks while providing extensive, granular
access control mechanisms and monitoring of critical parameters via the Simple
Network Management Protocol (SNMP). When selecting a computer system for use as
a dedicated Squid proxy, or caching servers, ensure your system is configured
with a large amount of physical memory, as Squid maintains an in-memory cache
for increased performance. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908251"></a><a name="_Toc242071445"><span style='mso-bookmark:
_Toc240908251'><span lang=EN-US>10.1 Installation</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>At a terminal prompt, enter the following command to install
the Squid server: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo apt-get install
squid<o:p></o:p></b></span></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908252"></a><a name="_Toc242071446"><span style='mso-bookmark:
_Toc240908252'><span lang=EN-US>10.2 Configuration</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Squid is configured by editing the
directives contained within the </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/squid/squid.conf</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> configuration file. The following examples illustrate some
of the directives which may be modified to affect the behavior of the Squid
server. For more in-depth configuration of Squid, see the References section.<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Prior to editing the configuration
file, you should make a copy of the original file and protect it from writing
so you will have the original settings as a reference, and to re-use as
necessary. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Copy the </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/squid/squid.conf</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file and protect it from writing with the following
commands entered at a terminal prompt:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo cp
/etc/squid/squid.conf /etc/squid/squid.conf.original</b><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo chmod a-w
/etc/squid/squid.conf.original</b></span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p></o:p></span></p>

<ul type=disc>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     text-align:justify;mso-list:l23 level1 lfo23;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>To set your Squid server to listen
     on TCP port 8888 instead of the default TCP port 3128, change the
     http_port directive as such: <o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l23 level1 lfo23;
tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><![if !supportLists]><span
lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>http_port
8888<o:p></o:p></span></p>

<ul type=disc>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     mso-list:l23 level1 lfo23;tab-stops:list 36.0pt'><span lang=EN-US
     style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
     "Times New Roman"'>Change the visible_hostname directive in order to give
     the Squid server a specific hostname. This hostname does not necessarily
     need to be the computer's hostname. In this example it is set to <i>weezie</i>
     <o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l23 level1 lfo23;
tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><![if !supportLists]><span
lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>visible_hostname
weezie<o:p></o:p></span></p>

<ul type=disc>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     text-align:justify;mso-list:l23 level1 lfo23;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>Again, Using Squid's access
     control, you may configure use of Internet services proxied by Squid to be
     available only users with certain Internet Protocol (IP) addresses. For
     example, we will illustrate access by users of the 192.168.42.0/24
     subnetwork only: <o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
margin-left:36.0pt'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Add the following to the <b>bottom</b>
of the ACL section of your </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/squid/squid.conf</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>acl
fortytwo_network src 192.168.42.0/24<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
margin-left:36.0pt'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Then, add the following to the <b>top</b>
of the http_access section of your </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/squid/squid.conf</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>http_access allow
fortytwo_network<o:p></o:p></span></p>

<ul type=disc>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
     text-align:justify;mso-list:l23 level1 lfo23;tab-stops:list 36.0pt'><span
     lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
     mso-bidi-font-family:"Times New Roman"'>Using the excellent access control
     features of Squid, you may configure use of Internet services proxied by
     Squid to be available only during normal business hours. For example,
     we'll illustrate access by employees of a business which is operating
     between <st1:time Minute="0" Hour="9" w:st="on">9:00AM</st1:time> and <st1:time
     Minute="0" Hour="17" w:st="on">5:00PM</st1:time>, Monday through Friday,
     and which uses the 10.1.42.0/42 subnetwork: <o:p></o:p></span></li>
</ul>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
margin-left:36.0pt'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Add the following to the <b>bottom</b>
of the ACL section of your </span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/squid/squid.conf</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>acl biz_network
src 10.1.42.0/24<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>acl biz_hours
time M T W T F <st1:time Minute="0" Hour="9" w:st="on">9:00-17:00</st1:time><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
margin-left:36.0pt'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Then, add the following to the <b>top</b>
of the http_access section of your </span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/squid/squid.conf</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>http_access allow
biz_network biz_hours<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>After making changes to the </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/squid/squid.conf</span><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
file, save the file and restart the <b>squid</b> server application to effect
the changes using the following command entered at a terminal prompt:</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo /etc/init.d/squid
restart</b><o:p></o:p></span></p>

<span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA'><br
clear=all style='mso-special-character:line-break;page-break-before:always'>
</span>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc240908253"></a><a name="_Toc242071447"><span style='mso-bookmark:
_Toc240908253'><span lang=EN-US>Chapter 11: DNS</span></span></a></h1>

<p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc242071448"><span lang=EN-US>11.1 Installation</span></a></h2>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>At a terminal prompt, enter the following
command to install <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>dns</span></strong>: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo apt-get
install bind9</span></strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'><o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>A very useful package for testing and
troubleshooting DNS issues is the dnsutils package. To install <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>dnsutils</span></strong>
enter the following: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo apt-get
install dnsutils<o:p></o:p></span></strong></p>

<pre><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<h2><a name="_Toc240908254"></a><a name="_Toc242071449"><span style='mso-bookmark:
_Toc240908254'><span lang=EN-US>11.2 Configuration</span></span></a></h2>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>There a many ways to configure <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>BIND9</span></strong>.
Some of the most common configurations are a caching nameserver, primary
master, and a as a secondary master. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l33 level1 lfo24;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>When
configured as a caching nameserver BIND9 will find the answer to name queries
and remember the answer when the domain is queried again. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l33 level1 lfo24;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>As a
primary master server BIND9 reads the data for a zone from a file on it's host
and is authoritative for that zone. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l33 level1 lfo24;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>In a
secondary master configuration BIND9 gets the zone data from another nameserver
authoritative for the zone. <o:p></o:p></span></p>

<p style='margin-left:18.0pt'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908255"></a><a name="_Toc242071450"><span style='mso-bookmark:
_Toc240908255'><span lang=EN-US>11.3 Overview</span></span></a></h2>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The DNS configuration files are stored
in the </span><code><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/bind</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> directory. The primary configuration file is </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/bind/named.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>include</span></em>
line specifies the filename which contains the DNS options. The <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>directory</span></em>
line in the </span><code><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/bind/named.conf.options</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file tells DNS where to look for files. All files BIND uses
will be relative to this directory. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
file named </span><code><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/bind/db.root</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> describes the root nameservers in the world. The servers
change over time, so the </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/bind/db.root</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file must be maintained now and then. This is usually done
as updates to the <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>bind9</span></strong> package. The <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>zone</span></em>
section defines a master server, and it is stored in a file mentioned in the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>file</span></em>
option. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>It is
possible to configure the same server to be a caching name server, primary
master, and secondary master. A server can be the Start of Authority (SOA) for
one zone, while providing secondary service for another zone. All the while
providing caching services for hosts on the local LAN. <o:p></o:p></span></p>

<p class=MsoNormal><a name="_Toc240908256"><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif'>Caching Nameserver</span></b></a><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
default configuration is setup to act as a caching server. All that is required
is simply adding the IP Addresses of your ISP's DNS servers. Simply uncomment
and edit the following in </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/bind/named.conf.options</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>: <o:p></o:p></span></p>

<pre style='margin-left:50.4pt'><span lang=EN-US style='font-size:11.0pt'>forwarders {<o:p></o:p></span></pre><pre
style='margin-left:50.4pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                </span>1.2.3.4;<o:p></o:p></span></pre><pre
style='margin-left:50.4pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                </span>5.6.7.8;<o:p></o:p></span></pre><pre
style='margin-left:50.4pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>           </span>};<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>Replace <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>1.2.3.4</span></em> and <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>5.6.7.8</span></em> with the IP Adresses of actual nameservers.<o:p></o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Now restart the DNS server, to enable
the new configuration. From a terminal prompt: <o:p></o:p></span></p>

<pre><strong><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>sudo /etc/init.d/bind9 restart<o:p></o:p></span></strong></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<p class=MsoNormal><a name="_Toc240908257"><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif'>Primary Master</span></b></a><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>In this section <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>BIND9</span></strong>
will be configured as the Primary Master for the domain <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>example.com</span></em>.
Simply replace <span class=italic>example.com</span> with your FQDN (Fully
Qualified Domain Name). <o:p></o:p></span></p>

<p class=MsoNormal><a name="_Toc240908258"><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif'>Forward Zone File</span></b></a><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To add a DNS zone to BIND9, turning
BIND9 into a Primary Master server, the first step is to edit </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/bind/named.conf.local</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>: <o:p></o:p></span></p>

<pre style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'>zone &quot;example.com&quot; {<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'><span
style='mso-tab-count:1'>       </span>type master;<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>file &quot;/etc/bind/db.example.com&quot;;<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'>};</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Now use an existing zone file as a
template to create the </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/bind/db.example.com</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file: <o:p></o:p></span></p>

<pre><strong><span lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><span
style='mso-tab-count:1'>       </span></span></strong><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo cp /etc/bind/db.local /etc/bind/db.example.com</span></strong><span
lang=EN-US style='font-size:11.0pt'><o:p></o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Edit
the new zone file </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/bind/db.example.com</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> change <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>localhost.</span></em> to the FQDN of
your server, leaving the additional &quot;.&quot; at the end. Change <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>127.0.0.1</span></em>
to the nameserver's IP Address and <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>root.localhost</span></em> to a valid
email address, but with a &quot;.&quot; instead of the usual &quot;@&quot; symbol,
again leaving the &quot;.&quot; at the end. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Also, create an <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>A
record</span></em> for <span class=italic>ns.example.com</span>. The name
server in this example: <o:p></o:p></span></p>

<pre><span lang=EN-US style='font-size:11.0pt'>;<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>; BIND data file for local loopback interface<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>;<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>$TTL<span style='mso-spacerun:yes'>    </span>604800<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>@<span style='mso-spacerun:yes'>       </span>IN<span style='mso-spacerun:yes'>      </span>SOA<span style='mso-spacerun:yes'>     </span>ns.example.com. root.example.com. (<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>             </span><span style='mso-spacerun:yes'>                 </span>2<span style='mso-spacerun:yes'>         </span>; Serial<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                         </span>604800<span style='mso-spacerun:yes'>         </span>; Refresh<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                          </span>86400<span style='mso-spacerun:yes'>         </span>; Retry<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                        </span>2419200<span style='mso-spacerun:yes'>         </span>; Expire<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                         </span>604800 )<span style='mso-spacerun:yes'>       </span>; Negative Cache TTL<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>;<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>@<span style='mso-spacerun:yes'>       </span>IN<span style='mso-spacerun:yes'>      </span>NS<span style='mso-spacerun:yes'>      </span>ns.example.com.<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>@<span style='mso-spacerun:yes'>       </span>IN<span style='mso-spacerun:yes'>      </span>A<span style='mso-spacerun:yes'>       </span>127.0.0.1<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>@<span style='mso-spacerun:yes'>       </span>IN<span style='mso-spacerun:yes'>      </span>AAAA<span style='mso-spacerun:yes'>    </span>::1<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>ns<span style='mso-spacerun:yes'>      </span>IN<span style='mso-spacerun:yes'>      </span>A<span style='mso-spacerun:yes'>       </span>192.168.1.10<o:p></o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>You
must increment the <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Serial Number</span></em> every time
you make changes to the zone file. If you make multiple changes before restarting
BIND9, simply increment the Serial once. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Now, you can add DNS records to the
bottom of the zone file <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Many
admins like to use the last date edited as the serial of a zone, such as <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>2007010100</span></em>
which is yyyymmddss (where <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>ss</span></em> is the Serial Number)<o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Once you have made a change to the zone
file <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>BIND9</span></strong> will need to be restarted for the
changes to take effect: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/bind9 restart<o:p></o:p></span></strong></p>

<pre><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<p class=MsoNormal><b><span lang=EN-US style='font-size:11.0pt;font-family:
"Arial",sans-serif'>Reverse Zone File<o:p></o:p></span></b></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Now that the zone is setup and
resolving names to IP Adresses a <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Reverse zone</span></em> is also
required. A Reverse zone allows DNS to resolve an address to a name. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Edit /etc/bind/named.conf.local and add
the following: <o:p></o:p></span></p>

<pre style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>zone &quot;1.168.192.in-addr.arpa&quot; {<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>type master;<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>notify no;<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>file &quot;/etc/bind/db.192&quot;;<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>};<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre><pre style='text-align:justify'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>Replace <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>1.168.192</span></em> with the first three octets of whatever network you are using. Also, name the zone file <code><span
style='mso-ansi-font-size:11.0pt;mso-bidi-font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/bind/db.192</span></code> appropriately. It should match the first octet of your network.</span><span
lang=EN-US style='font-size:11.0pt'><o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Now create the </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/bind/db.192</span></code><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
file: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo cp
/etc/bind/db.127 /etc/bind/db.192</span></strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Next edit </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/bind/db.192</span></code><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
changing the basically the same options as </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/bind/db.example.com</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>: <o:p></o:p></span></p>

<pre><span lang=EN-US style='font-size:11.0pt'>;<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>; BIND reverse data file for local loopback interface<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>;<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>$TTL<span style='mso-spacerun:yes'>    </span>604800<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>@<span style='mso-spacerun:yes'>       </span>IN<span style='mso-spacerun:yes'>      </span>SOA<span style='mso-spacerun:yes'>     </span>ns.example.com. root.example.com. (<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                              </span>2<span style='mso-spacerun:yes'>         </span>; Serial<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                         </span>604800<span style='mso-spacerun:yes'>         </span>; Refresh<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                          </span>86400<span style='mso-spacerun:yes'>         </span>; Retry<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                        </span>2419200<span style='mso-spacerun:yes'>         </span>; Expire<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>                         </span>604800 )<span style='mso-spacerun:yes'>       </span>; Negative Cache TTL<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>;<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>@<span style='mso-spacerun:yes'>       </span>IN<span style='mso-spacerun:yes'>      </span>NS<span style='mso-spacerun:yes'>      </span>ns.<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt'>10<span style='mso-spacerun:yes'>      </span>IN<span style='mso-spacerun:yes'>      </span>PTR<span style='mso-spacerun:yes'>     </span>ns.example.com.<o:p></o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Serial
Number</span></em> in the Reverse zone needs to be incremented on each changes
as well. For each <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>A record</span></em> you configure in </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/bind/db.example.com</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> you need to create a <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>PTR record</span></em> in </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/bind/db.192</span></code><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>.
<o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>After creating the reverse zone file
restart <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>BIND9</span></strong>: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/bind9 restart<o:p></o:p></span></strong></p>

<pre><strong><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></strong></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<p class=MsoNormal><a name="_Toc240908259"><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif'>Secondary Master</span></b></a><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Once a
<em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Primary
Master</span></em> has been configured a <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Secondary Master</span></em> is needed
in order to maintain the availability of the domain should the Primary become
unavailable. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>First,
on the Primary Master server, the zone transfer needs to be allowed. Add the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>allow-transfer</span></em>
option to the example Forward and Reverse zone definitions in </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/bind/named.conf.local</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>: <o:p></o:p></span></p>

<pre style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>zone &quot;example.com&quot; {<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>type master;<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><span
style='mso-tab-count:1'> </span>file &quot;/etc/bind/db.example.com&quot;;<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>allow-transfer { 192.168.1.11; };<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>};<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><o:p>&nbsp;</o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>zone &quot;1.168.192.in-addr.arpa&quot; {<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>type master;<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>notify no;<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>file &quot;/etc/bind/db.192&quot;;<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'><span
style='mso-tab-count:1'> </span>allow-transfer { 192.168.1.11; };<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><span style='mso-tab-count:1'>                   </span>};<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>Replace <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>192.168.1.11</span></em> with the IP Address of your Secondary nameserver<o:p></o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Next, on the Secondary Master, install
the <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>bind9</span></strong> package the same way as on the
Primary. Then edit the </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/bind/named.conf.local</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> and add the following declarations for the Forward and
Reverse zones: <o:p></o:p></span></p>

<pre style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'>zone &quot;example.com&quot; {<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'><span
style='mso-tab-count:1'>       </span>type slave;<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>file &quot;/var/cache/bind/db.example.com&quot;;<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>masters { 192.168.1.10; };<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'>};<span style='mso-spacerun:yes'>        </span><o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>      </span><o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'>zone &quot;1.168.192.in-addr.arpa&quot; {<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'><span
style='mso-tab-count:1'>       </span>type slave;<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>file &quot;/var/cache/bind/db.192&quot;;<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'><span style='mso-spacerun:yes'>        </span>masters { 192.168.1.10; };<o:p></o:p></span></pre><pre
style='margin-left:45.8pt'><span lang=EN-US style='font-size:11.0pt'>};<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre><pre><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>Replace <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>192.168.1.10</span></em> with the IP Address of your Primary nameserver</span><span
lang=EN-US style='font-size:11.0pt'><o:p></o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Restart <strong><span style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>BIND9</span></strong>
on the Secondary Master: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/bind9 restart</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>In </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/var/log/syslog</span></code><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
you should see something similar to: <o:p></o:p></span></p>

<pre style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>slave zone &quot;example.com&quot; (IN) loaded (serial 6)<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>slave zone &quot;100.18.172.in-addr.arpa&quot; (IN) loaded (serial 3)</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'> <o:p></o:p></span></pre><pre><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>Note: A zone is only transferred if the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>Serial Number</span></em> on the Primary is larger than the one on the Secondary.<o:p></o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'> The default directory for non-authoritative zone files is <code><span
style='mso-ansi-font-size:11.0pt;mso-bidi-font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/var/cache/bind/</span></code>.<span style='mso-spacerun:yes'>  </span></span><span
lang=EN-US style='font-size:11.0pt'><o:p></o:p></span></pre>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA'><br
clear=all style='mso-special-character:line-break;page-break-before:always'>
</span>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc240908260"></a><a name="_Toc242071451"><span style='mso-bookmark:
_Toc240908260'><span lang=EN-US>Chapter 12: HTTPD - Apache2 Web Server</span></span></a></h1>

<h1><!--[if supportFields]><span lang=EN-US><span style='mso-element:field-begin'></span><span
style='mso-spacerun:yes'> </span>XE &quot;HTTPD - Apache2 Web Server&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--></h1>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Apache
is the most commonly used Web Server on Linux systems. Web Servers are used to
serve Web Pages requested by client computers. Clients typically request and
view Web Pages using Web Browser applications such as <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Firefox</span></strong>,
<strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Opera</span></strong>, or <strong><span style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Mozilla</span></strong>.<o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'><span
style='mso-spacerun:yes'> </span>The most common protocol used to transfer Web
pages is the Hyper Text Transfer Protocol (HTTP). Protocols such as Hyper Text
Transfer Protocol over Secure Sockets Layer (HTTPS), and File Transfer Protocol
(FTP), a protocol for uploading and downloading files, are also supported.<o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Apache
Web Servers are often used in combination with the <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>MySQL</span></strong>
database engine, the HyperText Preprocessor (<strong><span style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>PHP</span></strong>)
scripting language, and other popular scripting languages such as <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Python</span></strong>
and <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Perl</span></strong>. This configuration is termed LAMP
(Linux, Apache, MySQL and Perl/Python/PHP) and forms a powerful and robust
platform for the development and deployment of Web-based applications.<o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908261"></a><a name="_Toc242071452"><span style='mso-bookmark:
_Toc240908261'><span lang=EN-US>12.1 Installation</span></span></a></h2>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The Apache2 web server is available in
Ubuntu Linux. To install Apache2: <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l15 level1 lfo25;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>At a
terminal prompt enter the following command: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-spacerun:yes'> </span><span
style='mso-tab-count:1'>  </span></span></strong><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo apt-get
install apache2</span></strong><strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New";font-weight:normal'><o:p></o:p></span></strong></p>

<pre><strong><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></strong></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<h2><a name="_Toc240908262"></a><a name="_Toc242071453"><span style='mso-bookmark:
_Toc240908262'><span lang=EN-US>12.2 Configuration</span></span></a></h2>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Apache2
is configured by placing <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>directives</span></em> in plain text
configuration files. The configuration files are separated between the
following files and directories: <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l17 level1 lfo26;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>apache2.conf:</span></em><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> the main Apache2 configuration file. Contains settings that
are <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>global</span></em> to Apache2. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l17 level1 lfo26;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>conf.d:</span></em><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> contains configuration files which apply <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>globally</span></em>
to Apache. Other packages that use Apache2 to serve content may add files, or
symlinks, to this directory. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l17 level1 lfo26;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>envvars:</span></em><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> file where Apache2 <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>environment</span></em> variables are
set. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l17 level1 lfo26;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>httpd.conf:</span></em><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> historically the main Apache2 configuration file, named
after the <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>httpd</span></strong> daemon. The file can be used for <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>user
specific</span></em> configuration options that globally effect Apache2. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l17 level1 lfo26;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>mods-available:</span></em><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> this directory contains configuration files to both load <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>modules</span></em>
and configure them. Not all modules will have specific configuration files,
however. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l17 level1 lfo26;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>mods-enabled:</span></em><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> holds <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>symlinks</span></em> to the files in </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/apache2/mods-available</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. When a module configuration file is symlinked it will be
enabled the next time <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>apache2</span></strong> is restarted. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l17 level1 lfo26;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>ports.conf:</span></em><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> houses the directives that determine which TCP ports
Apache2 is listening on. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l17 level1 lfo26;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>sites-available:</span></em><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> this directory has configuration files for Apache <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Virtual
Hosts</span></em>. Virtual Hosts allow Apache2 to be configured for multiple
sites that have separate configurations. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l17 level1 lfo26;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><em><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>sites-enabled:</span></em><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> like mods-enabled, </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>sites-enabled</span></code><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
contains symlinks to the </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/apache2/sites-available</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> directory. Similarly when a configuration file in
sites-available is symlinked it will be active once Apache is restarted. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>In
addition, other configuration files may be added using the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Include</span></em>
directive, and wildcards can be used to include many configuration files. Any
directive may be placed in any of these configuration files. Changes to the
main configuration files are only recognized by Apache2 when it is started or
restarted. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
server also reads a file containing mime document types; the filename is set by
the <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>TypesConfig</span></em> directive, and is </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/mime.types</span></code><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
by default.<o:p></o:p></span></p>

<h3 style='margin-left:0cm;text-align:justify;text-indent:0cm;mso-list:l35 level3 lfo33'><a
name="_Toc240908263"><span lang=EN-US><o:p>&nbsp;</o:p></span></a></h3>

<h2 style='text-align:justify'><span style='mso-bookmark:_Toc240908263'><a
name="_Toc242071454"><span lang=EN-US>12.3 Basic Settings</span></a></span></h2>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>This
section explains Apache2 server essential configuration parameters.<span
style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l25 level1 lfo27;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Apache2
ships with a virtual-host-friendly default configuration. That is, it is
configured with a single default virtual host (using the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>VirtualHost</span></em>
directive) which can modified or used as-is if you have a single site, or used
as a template for additional virtual hosts if you have multiple sites. If left
alone, the default virtual host will serve as your default site, or the site
users will see if the URL they enter does not match the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>ServerName</span></em>
directive of any of your custom sites. To modify the default virtual host, edit
the file </span><code><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/apache2/sites-available/default</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. <o:p></o:p></span></p>

<table class=MsoNormalTable border=0 cellspacing=3 cellpadding=0
 style='mso-cellspacing:1.5pt;margin-left:36.0pt;mso-yfti-tbllook:1184'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td valign=top style='padding:.75pt .75pt .75pt .75pt'>
  <p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
  font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
  directives set for a virtual host only apply to that particular virtual host.
  If a directive is set server-wide and not defined within the virtual host
  settings, the default setting is used. For example, you can define a
  Webmaster email address and not define individual email addresses for each
  virtual host. <o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l25 level1 lfo27;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>If you
wish to configure a new virtual host or site, copy that file into the same
directory with a name you choose. For example: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo cp
/etc/apache2/sites-available/default /etc/apache2/sites-available/mynewsite</span></strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l25 level1 lfo27;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Edit
the new file to configure the new site using some of the directives described
below. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l25 level1 lfo27;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>ServerAdmin</span></em>
directive specifies the email address to be advertised for the server's
administrator. The default value is webmaster@localhost. This should be changed
to an email address that is delivered to you (if you are the server's
administrator). If your website has a problem, Apache2 will display an error
message containing this email address to report the problem to. Find this
directive in your site's configuration file in /etc/apache2/sites-available. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l25 level1 lfo27;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Listen</span></em>
directive specifies the port, and optionally the IP address, Apache2 should
listen on. If the IP address is not specified, Apache2 will listen on all IP
addresses assigned to the machine it runs on. The default value for the Listen
directive is 80. Change this to 127.0.0.1:80 to cause Apache2 to listen only on
your loopback interface so that it will not be available to the Internet, to
(for example) 81 to change the port that it listens on, or leave it as is for
normal operation. This directive can be found and changed in its own file, </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/apache2/ports.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l25 level1 lfo27;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>ServerName</span></em>
directive is optional and specifies what FQDN your site should answer to. The
default virtual host has no ServerName directive specified, so it will respond
to all requests that do not match a ServerName directive in another virtual
host. If you have just acquired the domain name ubunturocks.com and wish to
host it on your Ubuntu server, the value of the ServerName directive in your
virtual host configuration file should be ubunturocks.com. Add this directive
to the new virtual host file you created earlier (</span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/apache2/sites-available/mynewsite</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>). <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>You may also want your site to respond to
www.ubunturocks.com, since many users will assume the www prefix is
appropriate. Use the <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>ServerAlias</span></em> directive for
this. You may also use wildcards in the ServerAlias directive. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>For example, the following configuration will cause your
site to respond to any domain request ending in <em><span style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>.ubunturocks.com</span></em>.
<o:p></o:p></span></p>

<pre style='margin-left:36.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>ServerAlias *.ubunturocks.com<o:p></o:p></span></pre>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l25 level1 lfo27;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>DocumentRoot</span></em>
directive specifies where Apache should look for the files that make up the
site. The default value is /var/www. No site is configured there, but if you
uncomment the <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>RedirectMatch</span></em> directive in </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/apache2/apache2.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> requests will be redirected to /var/www/apache2-default
where the default Apache2 site awaits. Change this value in your site's virtual
host file, and remember to create that directory if necessary! <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
/etc/apache2/sites-available directory is <strong><span style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>not</span></strong>
parsed by Apache2. Symbolic links in /etc/apache2/sites-enabled point to
&quot;available&quot; sites. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Enable
the new <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>VirtualHost</span></em> using the <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>a2ensite</span></strong>
utility and restart Apache: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo a2ensite
mynewsite</span></strong><span lang=EN-US style='font-size:11.0pt;font-family:
"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/apache2 restart<o:p></o:p></span></strong></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></strong></p>

<pre style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>Be sure to replace <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>mynewsite</span></em> with a more descriptive name for the VirtualHost. One method is to name the file after the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>ServerName</span></em> directive of the VirtualHost.<o:p></o:p></span></pre>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Similarly, use the <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>a2dissite</span></strong>
utility to disable sites. This is can be useful when troubleshooting
configuration problems with multiple VirtualHosts: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo a2dissite
mynewsite</span></strong><span lang=EN-US style='font-size:11.0pt;font-family:
"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/apache2 restart<o:p></o:p></span></strong></p>

<pre><strong><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></strong></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<h2><a name="_Toc242071455"><span lang=EN-US>12.4 Default Settings</span></a></h2>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>This
section explains configuration of the Apache2 server default settings. For
example, if you add a virtual host, the settings you configure for the virtual
host take precedence for that virtual host. For a directive not defined within
the virtual host settings, the default value is used. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l24 level1 lfo28;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>DirectoryIndex</span></em>
is the default page served by the server when a user requests an index of a
directory by specifying a forward slash (/) at the end of the directory name. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>For example, when a user requests the page
http://www.example.com/this_directory/, he or she will get either the
DirectoryIndex page if it exists, a server-generated directory list if it does
not and the Indexes option is specified, or a Permission Denied page if neither
is true. The server will try to find one of the files listed in the
DirectoryIndex directive and will return the first one it finds. If it does not
find any of these files and if Options Indexes is set for that directory, the server
will generate and return a list, in HTML format, of the subdirectories and
files in the directory. The default value, found in </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/apache2/apache2.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> is &quot; index.html index.cgi index.pl index.php
index.xhtml&quot;. Thus, if Apache2 finds a file in a requested directory
matching any of these names, the first will be displayed. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l24 level1 lfo28;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>ErrorDocument</span></em>
directive allows you to specify a file for Apache to use for specific error
events. For example, if a user requests a resource that does not exist, a 404
error will occur, and per Apache2's default configuration, the file </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/usr/share/apache2/error/HTTP_NOT_FOUND.html.var </span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>will be displayed. That file is not in the server's
DocumentRoot, but there is an Alias directive in </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/apache2/apache2.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> that redirects requests to the /error directory to </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/usr/share/apache2/error/</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>To see a list of the default ErrorDocument directives, use
this command: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-spacerun:yes'> </span></span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> grep
ErrorDocument /etc/apache2/apache2.conf</span></strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l24 level1 lfo28;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>By
default, the server writes the transfer log to the file </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/var/log/apache2/access.log</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. You can change this on a per-site basis in your virtual
host configuration files with the <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>CustomLog</span></em> directive, or
omit it to accept the default, specified in </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/apache2/apache2.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. You may also specify the file to which errors are logged,
via the <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>ErrorLog</span></em> directive, whose default is </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/var/log/apache2/error.log</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. These are kept separate from the transfer logs to aid in
troubleshooting problems with your Apache2 server. You may also specify the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>LogLevel</span></em>
(the default value is &quot;warn&quot;) and the <em><span style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>LogFormat</span></em>
(see </span><code><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/apache2/apache2.conf</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> for the default value). <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l24 level1 lfo28;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Some
options are specified on a per-directory basis rather than per-server. <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Options</span></em>
is one of these directives. A Directory stanza is enclosed in XML-like tags,
like so: <o:p></o:p></span></p>

<pre style='margin-left:18.0pt'><span lang=EN-US style='font-size:11.0pt'>&lt;Directory /var/www/mynewsite&gt;<o:p></o:p></span></pre><pre
style='margin-left:18.0pt'><span lang=EN-US style='font-size:11.0pt'>...<o:p></o:p></span></pre><pre
style='margin-left:18.0pt'><span lang=EN-US style='font-size:11.0pt'>&lt;/Directory&gt;<o:p></o:p></span></pre>

<p style='margin-left:36.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Options</span></em> directive within a
Directory stanza accepts one or more of the following values (among others),
separated by spaces: <o:p></o:p></span></p>

<p style='margin-left:72.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l24 level2 lfo28;tab-stops:list 72.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Courier New";
mso-fareast-font-family:"Courier New"'><span style='mso-list:Ignore'>o<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>ExecCGI</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
- Allow execution of CGI scripts. CGI scripts are not executed if this option
is not chosen. <o:p></o:p></span></p>

<table class=MsoNormalTable border=0 cellspacing=3 cellpadding=0
 style='mso-cellspacing:1.5pt;margin-left:72.0pt;mso-yfti-tbllook:1184'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;mso-yfti-lastrow:yes'>
  <td valign=top style='padding:.75pt .75pt .75pt .75pt'>
  <p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
  font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Most
  files should not be executed as CGI scripts. This would be very dangerous.
  CGI scripts should kept in a directory separate from and outside your
  DocumentRoot, and only this directory should have the ExecCGI option set.
  This is the default, and the default location for CGI scripts is </span><code><span
  lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Courier New"'>/usr/lib/cgi-bin</span></code><span
  lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
  mso-bidi-font-family:"Times New Roman"'>. <o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p style='margin-left:72.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l24 level2 lfo28;tab-stops:list 72.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Courier New";
mso-fareast-font-family:"Courier New"'><span style='mso-list:Ignore'>o<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Includes</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
- Allow server-side includes. Server-side includes allow an HTML file to <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>include</span></em>
other files. This is not a common option.<span style='mso-spacerun:yes'> 
</span><o:p></o:p></span></p>

<p style='margin-left:72.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l24 level2 lfo28;tab-stops:list 72.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Courier New";
mso-fareast-font-family:"Courier New"'><span style='mso-list:Ignore'>o<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>IncludesNOEXEC</span></strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> - Allow server-side includes, but disable the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>#exec</span></em>
and <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>#include</span></em> commands in CGI scripts. <o:p></o:p></span></p>

<p style='margin-left:72.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l24 level2 lfo28;tab-stops:list 72.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Courier New";
mso-fareast-font-family:"Courier New"'><span style='mso-list:Ignore'>o<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Indexes</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
- Display a formatted list of the directory's contents, if no <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>DirectoryIndex</span></em>
(such as index.html) exists in the requested directory.<o:p></o:p></span></p>

<p style='margin-left:72.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-spacerun:yes'> </span>For security reasons,
this should usually not be set, and certainly should not be set on your
DocumentRoot directory. Enable this option carefully on a per-directory basis
only if you are certain you want users to see the entire contents of the
directory.<o:p></o:p></span></p>

<p style='margin-left:72.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l24 level2 lfo28;tab-stops:list 72.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Courier New";
mso-fareast-font-family:"Courier New"'><span style='mso-list:Ignore'>o<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Multiview</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>
- Support content-negotiated multiviews; this option is disabled by default for
security reasons.<span style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<p style='margin-left:72.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l24 level2 lfo28;tab-stops:list 72.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Courier New";
mso-fareast-font-family:"Courier New"'><span style='mso-list:Ignore'>o<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>SymLinksIfOwnerMatch</span></strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> - Only follow symbolic links if the target file or
directory has the same owner as the link. <o:p></o:p></span></p>

<p style='margin-left:54.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908264"></a><a name="_Toc242071456"><span style='mso-bookmark:
_Toc240908264'><span lang=EN-US>12.5 httpd Settings</span></span></a></h2>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>This section explains some basic <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>httpd</span></strong>
daemon configuration settings. <o:p></o:p></span></p>

<p style='text-align:justify'><strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>LockFile</span></strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> - The LockFile directive sets the path to the lockfile used
when the server is compiled with either USE_FCNTL_SERIALIZED_ACCEPT or
USE_FLOCK_SERIALIZED_ACCEPT. It must be stored on the local disk. It should be
left to the default value unless the logs directory is located on an NFS share.
If this is the case, the default value should be changed to a location on the
local disk and to a directory that is readable only by root. <o:p></o:p></span></p>

<p style='text-align:justify'><strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>PidFile</span></strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> - The PidFile directive sets the file in which the server
records its process ID (pid). This file should only be readable by root. In
most cases, it should be left to the default value. <o:p></o:p></span></p>

<p style='text-align:justify'><strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>User</span></strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> - The User directive sets the userid used by the server to
answer requests. This setting determines the server's access. Any files
inaccessible to this user will also be inaccessible to your website's visitors.
The default value for User is www-data. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Unless
you know exactly what you are doing, do not set the User directive to root.
Using root as the User will create large security holes for your Web server.<o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
Group directive is similar to the User directive. Group sets the group under
which the server will answer requests. The default group is also www-data. <o:p></o:p></span></p>

<h4 style='margin-left:0cm;text-align:justify;text-indent:0cm;mso-list:l35 level4 lfo33'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Apache Modules<o:p></o:p></span></h4>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Apache
is a modular server. This implies that only the most basic functionality is
included in the core server. Extended features are available through modules
which can be loaded into Apache. By default, a base set of modules is included
in the server at compile-time. If the server is compiled to use dynamically
loaded modules, then modules can be compiled separately, and added at any time
using the LoadModule directive. Otherwise, Apache must be recompiled to add or
remove modules. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Ubuntu
compiles Apache2 to allow the dynamic loading of modules. Configuration
directives may be conditionally included on the presence of a particular module
by enclosing them in an <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>&lt;IfModule&gt;</span></em> block. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>You
can install additional Apache2 modules and use them with your Web server. For
example, run the following command from a terminal prompt to install the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>MySQL
Authentication</span></em> module: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-spacerun:yes'> </span></span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo apt-get
install libapache2-mod-auth-mysql</span></strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>See
the </span><code><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/apache2/mods-available</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> directory, for additional modules. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Use
the <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>a2enmod</span></strong> utility to enable a module: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo a2enmod
auth_mysql</span></strong><span lang=EN-US style='font-size:11.0pt;font-family:
"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/apache2 restart</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Similarly, <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>a2dismod</span></strong>
will disable a module: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo a2dismod
auth_mysql</span></strong><span lang=EN-US style='font-size:11.0pt;font-family:
"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/apache2 restart<o:p></o:p></span></strong></p>

<pre><strong><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></strong></pre><pre
style='text-align:justify'><b><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></b></pre>

<p class=MsoNormal style='text-align:justify'><a name="_Toc240908265"><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'>HTTPS
Configuration</span></b></a><b><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>mod_ssl</span></strong>
module adds an important feature to the Apache2 server - the ability to encrypt
communications. Thus, when your browser is communicating using SSL, the
https:// prefix is used at the beginning of the Uniform Resource Locator (URL)
in the browser navigation bar. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>mod_ssl</span></strong>
module is available in <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>apache2-common</span></strong> package.
Execute the following command from a terminal prompt to enable the <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>mod_ssl</span></strong>
module: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo a2enmod ssl</span></strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>There
is a default HTTPS configuration file in </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/apache2/sites-available/default-ssl</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. In order for <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Apache</span></strong> to provide
HTTPS, a <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>certificate</span></em> and <em><span style='font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>key</span></em>
file are also needed. The default HTTPS configuration will use a certificate
and key generated by the <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>ssl-cert</span></strong> package. They
are good for testing, but the auto-generated certificate and key should be
replaced by a certificate specific to the site or server.<span
style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>To
configure <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Apache</span></strong> for HTTPS, enter the following: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo a2ensite
default-ssl<o:p></o:p></span></strong></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'><o:p>&nbsp;</o:p></span></strong></p>

<pre style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>The directories <code><span
style='mso-ansi-font-size:11.0pt;mso-bidi-font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/ssl/certs</span></code> and <code><span
style='mso-ansi-font-size:11.0pt;mso-bidi-font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>/etc/ssl/private</span></code> are the default locations. If you install the certificate and key in another directory make sure to change <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>SSLCertificateFile</span></em> and <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>SSLCertificateKeyFile</span></em> appropriately.<o:p></o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>With
Apache now configured for HTTPS, restart the service to enable the new
settings: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/apache2 restart<o:p></o:p></span></strong></p>

<pre style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></pre><pre
style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>Depending on how you obtained your certificate you may need to enter a passphrase when <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>Apache</span></strong> starts.<o:p></o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>You
can access the secure server pages by typing https://your_hostname/url/ in your
browser address bar. <o:p></o:p></span></p>

<span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA'><br
clear=all style='mso-special-character:line-break;page-break-before:always'>
</span>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc240908266"></a><a name="_Toc242071457"><span style='mso-bookmark:
_Toc240908266'><span lang=EN-US>Chapter 13: MySQL</span></span></a></h1>

<h1><!--[if supportFields]><span lang=EN-US><span style='mso-element:field-begin'></span><span
style='mso-spacerun:yes'> </span>XE &quot;MySQL&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--></h1>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>MySQL is a fast, multi-threaded,
multi-user, and robust SQL database server. It is intended for
mission-critical, heavy-load production systems as well as for embedding into
mass-deployed software. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2 style='text-align:justify'><a name="_Toc240908267"></a><a
name="_Toc242071458"><span style='mso-bookmark:_Toc240908267'><span lang=EN-US>13.1
Installation</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To install MySQL, run the following
command from a terminal prompt: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo apt-get install
mysql-server</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>During the installation process you
will be prompted to enter a password for the <b>MySQL</b> root user. <o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Once the installation is complete, the
MySQL server should be started automatically. You can run the following command
from a terminal prompt to check whether the MySQL server is running: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo netstat -tap |
grep mysql</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>When you run this command, you should
see the following line or something similar: <o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>tcp <span
style='mso-spacerun:yes'>  </span>0<span style='mso-spacerun:yes'>  </span>0
localhost:mysql<span style='mso-spacerun:yes'>     </span>*:*<span
style='mso-spacerun:yes'>     </span>LISTEN<span style='mso-spacerun:yes'>     
</span>2556/mysqld<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>If the server is not running correctly,
you can type the following command to start it: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo /etc/init.d/mysql
restart<o:p></o:p></b></span></p>

<p class=MsoNormal style='text-align:justify;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></p>

<h2 style='text-align:justify'><a name="_Toc240908268"></a><a
name="_Toc242071459"><span style='mso-bookmark:_Toc240908268'><span lang=EN-US>13.2
Configuration</span></span></a></h2>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>You can edit the </span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/mysql/my.cnf</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> file
to configure the basic settings -- log file, port number, etc. For example, to
configure <b>MySQL</b> to listen for connections from network hosts, change the
<i>bind_address</i> directive to the server's IP address: <o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'>bind-address<span
style='mso-spacerun:yes'>            </span>= 192.168.0.5 <o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify;tab-stops:45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Replace 192.168.0.5 with the appropriate address.</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>After making a change to </span><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/mysql/my.cnf</span><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'> the <b>mysql</b>
daemon will need to be restarted: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo /etc/init.d/mysql
restart</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>If you would like to change the <b>MySQL</b> <i>root</i>
password, in a terminal enter: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$<b> sudo dpkg-reconfigure
mysql-server-5.0</b><o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>The <b>mysql</b> daemon will be stopped, and you will be
prompted to enter a new password. <o:p></o:p></span></p>

<b><span lang=EN-US style='font-size:16.0pt;font-family:"Cambria",serif;
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman";
mso-font-kerning:16.0pt;mso-ansi-language:EN-US;mso-fareast-language:EN-US;
mso-bidi-language:AR-SA'><br clear=all style='page-break-before:always'>
</span></b>

<h1><a name="_Toc240908269"></a><a name="_Toc242071460"><span style='mso-bookmark:
_Toc240908269'><span lang=EN-US>Chapter 14: Postfix (Mail server)</span></span></a></h1>

<h1><!--[if supportFields]><span lang=EN-US><span style='mso-element:field-begin'></span><span
style='mso-spacerun:yes'> </span>XE &quot;Postfix (Mail server)&quot; </span><![endif]--><!--[if supportFields]><span
lang=EN-US><span style='mso-element:field-end'></span></span><![endif]--></h1>

<p style='text-align:justify'><strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Postfix</span></strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> is the default Mail Transfer Agent (MTA) in Ubuntu. It
attempts to be fast and easy to administer and secure. It is compatible with
the MTA <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>sendmail</span></strong>. This section explains how to
install and configure <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>postfix</span></strong>. It also
explains how to set it up as an SMTP server using a secure connection (for
sending emails securely). <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908270"></a><a name="_Toc242071461"><span style='mso-bookmark:
_Toc240908270'><span lang=EN-US>14.1 Installation</span></span></a></h2>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To install <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>postfix</span></strong>
run the following command: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo apt-get
install postfix</span></strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'><o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Simply press return when the
installation process asks questions, the configuration will be done in greater
detail in the next stage. <o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<h2><a name="_Toc240908271"></a><a name="_Toc242071462"><span style='mso-bookmark:
_Toc240908271'><span lang=EN-US>14.2 Basic Configuration</span></span></a></h2>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>To configure <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>postfix</span></strong>,
run the following command: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
dpkg-reconfigure postfix</span></strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'><o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>The user interface will be displayed.
On each screen, select the following values: <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l21 level1 lfo29;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Internet
Site<o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l21 level1 lfo29;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>mail.example.com<o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l21 level1 lfo29;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>steve<o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l21 level1 lfo29;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>mail.example.com,
localhost.localdomain, localhost<o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l21 level1 lfo29;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>No<o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l21 level1 lfo29;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>127.0.0.0/8
[::ffff:127.0.0.0]/104 [::1]/128 192.168.0/24<o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l21 level1 lfo29;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>0<o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l21 level1 lfo29;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>+<o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-indent:-18.0pt;mso-list:l21 level1 lfo29;
tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US style='font-size:
10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>All<o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Replace mail.example.com with your mail
server hostname, 192.168.0/24 with the actual network and class range of your
mail server, and steve with the appropriate username.<o:p></o:p></span></p>

<p><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><a name="_Toc240908272"><span lang=EN-US><o:p>&nbsp;</o:p></span></a></p>

<p class=MsoNormal><span style='mso-bookmark:_Toc240908272'><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'>SMTP
Authentication</span></b></span><b><span lang=EN-US style='font-size:11.0pt;
font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>SMTP-AUTH
allows a client to identify itself through an authentication mechanism (SASL).
Transport Layer Security (TLS) should be used to encrypt the authentication
process. Once authenticated the SMTP server will allow the client to relay
mail. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Configuring
<strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Postfix</span></strong> for SMTP-AUTH is very simple using
the <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>dovecot-postfix</span></strong> package. This package will
install <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Dovecot</span></strong> and configure <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Postfix</span></strong>
to use it for both SASL authentication and as a Mail Delivery Agent (MDA). The
package also configures <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Dovecot</span></strong> for IMAP,
IMAPS, POP3, and POP3S. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>To
install the package, from a terminal prompt enter: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'><span style='mso-tab-count:1'>   </span></span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo apt-get
install dovecot-postfix</span></strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'><o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>You
should now have a working mail server, but there are a few options that you may
wish to further customize. For example, the package uses the certificate and
key from the <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>ssl-cert</span></strong> package, and in a production
environment you should use a certificate and key generated for the host.<span
style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Once
you have a customized certificate and key for the host, change the following
options in </span><code><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/postfix/main.cf</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>: <o:p></o:p></span></p>

<pre style='margin-left:50.4pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt'>smtpd_tls_cert_file = /etc/ssl/certs/ssl-mail.pem<o:p></o:p></span></pre><pre
style='margin-left:50.4pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt'>smtpd_tls_key_file = /etc/ssl/private/ssl-mail.key</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Then
restart Postfix: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/postfix restart<o:p></o:p></span></strong></p>

<pre style='text-align:justify'><strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></strong></pre><pre
style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<h2 style='text-align:justify'><a name="_Toc240908273"></a><a
name="_Toc242071463"><span style='mso-bookmark:_Toc240908273'><span lang=EN-US>14.3
Testing</span></span></a></h2>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>SMTP-AUTH
configuration is complete. Now it is time to test the setup. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>To see
if SMTP-AUTH and TLS work properly, run the following command: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> telnet
mail.example.com 25</span></strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'><o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>After
you have established the connection to the postfix mail server, type: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New"'>$ <b>ehlo mail.example.com</b><o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>If you
see the following lines among others, then everything is working perfectly.
Type <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>quit</span></strong> to exit. <o:p></o:p></span></p>

<pre style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>250-STARTTLS<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>250-AUTH LOGIN PLAIN<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>250-AUTH=LOGIN PLAIN<o:p></o:p></span></pre><pre
style='margin-left:43.2pt'><span lang=EN-US style='font-size:11.0pt'>250 8BITMIME</span><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p></o:p></span></pre><pre><span lang=EN-US style='font-size:
11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'><o:p>&nbsp;</o:p></span></pre><pre><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<p class=MsoNormal><a name="_Toc240908274"><b><span lang=EN-US
style='font-size:11.0pt;font-family:"Arial",sans-serif'>Troubleshooting</span></b></a><b><span
lang=EN-US style='font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></b></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>This
section introduces some common ways to determine the cause if problems arise. <o:p></o:p></span></p>

<h4 style='margin-left:0cm;text-align:justify;text-indent:0cm;mso-list:l35 level4 lfo33'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Escaping chroot<o:p></o:p></span></h4>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
Ubuntu <strong><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>postfix</span></strong> package will by default install into
a <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>chroot</span></em>
environment for security reasons. This can add greater complexity when
troubleshooting problems. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>To
turn off the chroot operation locate for the following line in the </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/postfix/master.cf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> configuration file: <o:p></o:p></span></p>

<pre style='text-align:justify'><span lang=EN-US style='font-size:11.0pt'>smtp<span style='mso-spacerun:yes'>      </span>inet<span style='mso-spacerun:yes'>  </span>n<span style='mso-spacerun:yes'>       </span>-<span style='mso-spacerun:yes'>       </span>-<span style='mso-spacerun:yes'>       </span>-<span style='mso-spacerun:yes'>       </span>-<span style='mso-spacerun:yes'>       </span>smtpd<o:p></o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>and
modify it as follows: <o:p></o:p></span></p>

<pre style='text-align:justify'><span lang=EN-US style='font-size:11.0pt'>smtp<span style='mso-spacerun:yes'>      </span>inet<span style='mso-spacerun:yes'>  </span>n<span style='mso-spacerun:yes'>       </span>-<span style='mso-spacerun:yes'>       </span>n<span style='mso-spacerun:yes'>       </span>-<span style='mso-spacerun:yes'>      </span><span style='mso-spacerun:yes'> </span>-<span style='mso-spacerun:yes'>       </span>smtpd<o:p></o:p></span></pre>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>You
will then need to restart Postfix to use the new configuration. From a terminal
prompt enter: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo
/etc/init.d/postfix restart</span></strong><span lang=EN-US style='font-size:
11.0pt;font-family:"Courier New"'><o:p></o:p></span></p>

<h4 style='margin-left:0cm;text-align:justify;text-indent:0cm;mso-list:l35 level4 lfo33'><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>Log Files<o:p></o:p></span></h4>

<p style='text-align:justify'><strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>Postfix</span></strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> sends all log messages to </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/var/log/mail.log</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>. However error and warning messages can sometimes get lost
in the normal log output so they are also logged to </span><code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/var/log/mail.err</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> and </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/var/log/mail.warn</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> respectively. <o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>To see
messages entered into the logs in real time you can use the <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>tail
-f</span></strong> command: <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> tail -f
/var/log/mail.err</span></strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'><o:p></o:p></span></p>

<p style='text-align:justify'><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>The
amount of detail that is recorded in the logs can be increased. Below are some
configuration options for increasing the log level for some of the areas
covered above. <o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l2 level1 lfo30;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>To
increase <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>TLS</span></em> activity logging set the <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>smtpd_tls_loglevel</span></em>
option to a value from 1 to 4. <o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:36.0pt'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo postconf -e
'smtpd_tls_loglevel = 4'</span></strong><span lang=EN-US style='font-size:11.0pt;
font-family:"Courier New"'><o:p></o:p></span></p>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l2 level1 lfo30;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>If you
are having trouble sending or receiving mail from a specific domain you can add
the domain to the <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>debug_peer_list</span></em> parameter. <o:p></o:p></span></p>

<pre style='margin-left:36.0pt;text-align:justify'><strong><span lang=EN-US
style='font-size:11.0pt;font-family:"Courier New";font-weight:normal'>$</span></strong><strong><span
lang=EN-US style='font-size:11.0pt;font-family:"Courier New"'> sudo postconf -e 'debug_peer_list = problem.domain'</span></strong><span
lang=EN-US style='font-size:11.0pt'><o:p></o:p></span></pre>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l2 level1 lfo30;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>You
can increase the verbosity of any <strong><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>Postfix</span></strong> daemon process
by editing the </span><code><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>/etc/postfix/master.cf</span></code><span
lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> and adding a <em><span style='font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'>-v</span></em> after the entry. For
example edit the <em><span style='font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'>smtp</span></em> entry: <o:p></o:p></span></p>

<pre style='margin-left:18.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt'>smtp<span style='mso-spacerun:yes'>      </span>unix<span style='mso-spacerun:yes'>  </span>-<span style='mso-spacerun:yes'>       </span>-<span style='mso-spacerun:yes'>       </span>-<span style='mso-spacerun:yes'>       </span>-<span style='mso-spacerun:yes'>     </span>-<span style='mso-spacerun:yes'>       </span>smtp v<o:p></o:p></span></pre><pre
style='margin-left:18.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre><pre style='margin-left:18.0pt;
text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Courier New"'>It is important to note that after making one of the logging changes above the <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>Postfix</span></strong> process will need to be reloaded in order to recognize the new configuration: <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>sudo /etc/init.d/postfix reload</span></strong><o:p></o:p></span></pre><pre
style='margin-left:18.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<p style='margin-left:36.0pt;text-align:justify;text-indent:-18.0pt;mso-list:
l37 level1 lfo31;tab-stops:list 36.0pt'><![if !supportLists]><span lang=EN-US
style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:11.0pt;
font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>To
increase the amount of information logged when troubleshooting <em><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Times New Roman"'>SASL</span></em>
issues you can set the following options in </span><code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>/etc/dovecot/dovecot.conf</span></code><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Times New Roman"'> <o:p></o:p></span></p>

<pre style='margin-left:18.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt'>auth_debug=yes<o:p></o:p></span></pre><pre
style='margin-left:18.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt'>auth_debug_passwords=yes<o:p></o:p></span></pre><pre
style='margin-left:18.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt'><o:p>&nbsp;</o:p></span></pre><pre style='margin-left:
18.0pt;text-align:justify'><span lang=EN-US style='font-size:11.0pt;font-family:
"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>Just like <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>Postfix</span></strong> if you change a <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>Dovecot</span></strong> configuration the process will need to be reloaded: <strong><span
style='font-family:"Calibri",sans-serif;mso-bidi-font-family:"Courier New"'>sudo /etc/init.d/dovecot reload</span></strong>.<o:p></o:p></span></pre><pre
style='margin-left:18.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'>Some of the options above can drastically increase the amount of information sent to the log files. Remember to return the log level back to normal after you have corrected the problem. Then reload the appropriate daemon for the new configuration to take affect.</span><span
lang=EN-US style='font-size:11.0pt'><o:p></o:p></span></pre><pre
style='margin-left:18.0pt;text-align:justify'><span lang=EN-US
style='font-size:11.0pt;font-family:"Calibri",sans-serif;mso-bidi-font-family:
"Courier New"'><o:p>&nbsp;</o:p></span></pre>

<p class=MsoNormal><span lang=EN-US style='font-size:11.0pt;font-family:"Calibri",sans-serif;
mso-bidi-font-family:"Times New Roman"'><o:p>&nbsp;</o:p></span></p>

</div>

</body>

</html>
