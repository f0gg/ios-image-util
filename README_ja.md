ios-image-util
==============

OVERVIEW

このjavaプログラムは、iOS6以前、およびiOS7で必要なアイコン＆起動イメージを全てのサイズで生成します。
アイコンはiOS6用とiOS7用で若干異なる為、両方指定できるようにしてあります（ズレても構わなければ１つで全てのアイコンも出力できます）。
起動イメージは1536×1536ピクセルの正方形イメージを用意すると、全てのサイズを出力します。その際、元画像は真ん中に配置され、元画像の左上の色が背景色になります。

何か問題がある場合や仕様にご不満の場合は、自由に編集してください。コンパイルをしたくない場合は、起動可能なjarファイルをダウンロードして使ってください。

<img src="https://github.com/f0gg/ios-image-util/blob/master/docs/screen.png?raw=true" />

以下、出力されるファイル一覧。
<table>
	<tr>
		<th>Version</th>
		<th>Type</th>
		<th>Filename</th>
		<th>Width</th>
		<th>Height</th>
		<th>Description</th>
	</tr>
	<tr>
		<td rowspan="15">iOS6 or lower</td>
		<td rowspan="8">Icon</td>
		<td>Icon.png</td>
		<td align="right">57</td>
		<td align="right">57</td>
		<td>iPhone 3G / 3GS</td>
	</tr>
	<tr>
		<td>Icon@2x.png</td>
		<td align="right">114</td>
		<td align="right">114</td>
		<td>iPhone4 or later</td>
	</tr>
	<tr>
		<td>Icon-72.png</td>
		<td align="right">72</td>
		<td align="right">72</td>
		<td>iPad / iPad2 / iPad mini</td>
	</tr>
	<tr>
		<td>Icon-72@2x.png</td>
		<td align="right">144</td>
		<td align="right">144</td>
		<td>iPad3 or later</td>
	</tr>
	<tr>
		<td>Icon-Small.png</td>
		<td align="right">29</td>
		<td align="right">29</td>
		<td>iPhone3G / 3GS / iPad / iPad2 / iPad mini</td>
	</tr>
	<tr>
		<td>Icon-Small@2x.png</td>
		<td align="right">58</td>
		<td align="right">58</td>
		<td>iPhone4 / iPad3 or later</td>
	</tr>
	<tr>
		<td>Icon-Small-50.png</td>
		<td align="right">50</td>
		<td align="right">50</td>
		<td>iPad / iPad2 / iPad mini</td>
	</tr>
	<tr>
		<td>Icon-Small-50@2x.png</td>
		<td align="right">100</td>
		<td align="right">100</td>
		<td>iPad3 or later</td>
	</tr>
	<tr>
		<td rowspan="7">Splash</td>
		<td>Default.png</td>
		<td align="right">320</td>
		<td align="right">480</td>
		<td>iPhone 3G / 3GS</td>
	</tr>
	<tr>
		<td>Default@2x.png</td>
		<td align="right">640</td>
		<td align="right">960</td>
		<td>iPhone4 / 4S</td>
	</tr>
	<tr>
		<td>Default-568h@2x.png</td>
		<td align="right">640</td>
		<td align="right">1136</td>
		<td>iPhone 5 or later</td>
	</tr>
	<tr>
		<td>Default-Portrait.png</td>
		<td align="right">768</td>
		<td align="right">1004</td>
		<td>iPad / iPad2 / iPad mini</td>
	</tr>
	<tr>
		<td>Default-Portrait@2x.png</td>
		<td align="right">1536</td>
		<td align="right">2008</td>
		<td>iPad 3 or later</td>
	</tr>
	<tr>
		<td>Default-Landscape.png</td>
		<td align="right">1024</td>
		<td align="right">748</td>
		<td>iPad / iPad2 / iPad mini</td>
	</tr>
	<tr>
		<td>Default-Landscape@2x.png</td>
		<td align="right">2048</td>
		<td align="right">1496</td>
		<td>iPad 3 or later</td>
	</tr>
	<tr>
		<td rowspan="11">iOS7 or upper</td>
		<td rowspan="7">Icon</td>
		<td>Icon-60@2x.png</td>
		<td align="right">120</td>
		<td align="right">120</td>
		<td>iPhone4 or later</td>
	</tr>
	<tr>
		<td>Icon-76.png</td>
		<td align="right">76</td>
		<td align="right">76</td>
		<td>iPad / iPad2 / iPad mini</td>
	</tr>
	<tr>
		<td>Icon-76@2x.png</td>
		<td align="right">152</td>
		<td align="right">152</td>
		<td>iPad3 or later</td>
	</tr>
	<tr>
		<td>Icon-Small-40.png</td>
		<td align="right">40</td>
		<td align="right">40</td>
		<td>iPad2 / iPad mini</td>
	</tr>
	<tr>
		<td>Icon-Small-40@2x.png</td>
		<td align="right">80</td>
		<td align="right">80</td>
		<td>iPhone4 / iPad3 or later</td>
	</tr>
	<tr>
		<td>iTunesArtwork</td>
		<td align="right">512</td>
		<td align="right">512</td>
		<td>iTunes Artwork</td>
	</tr>
	<tr>
		<td>iTunesArtwork@2x</td>
		<td align="right">1024</td>
		<td align="right">1024</td>
		<td>iTunes Artwork(Retina)</td>
	</tr>
	<tr>
		<td rowspan="4">Splash</td>
		<td>Default-Portrait-1024h.png</td>
		<td align="right">768</td>
		<td align="right">1024</td>
		<td>iPad / iPad2 / iPad mini</td>
	</tr>
	<tr>
		<td>Default-Portrait-1024h@2x.png</td>
		<td align="right">1536</td>
		<td align="right">2048</td>
		<td>iPad 3 or later</td>
	</tr>
	<tr>
		<td>Default-Landscape-768h.png</td>
		<td align="right">1024</td>
		<td align="right">768</td>
		<td>iPad 3 or later</td>
	</tr>
	<tr>
		<td>Default-Landscape-768h@2x.png</td>
		<td align="right">2048</td>
		<td align="right">1536</td>
		<td>iPad 3 or later</td>
	</tr>
</table>

PREREQUISITES

- JDK 1.6 or higher


