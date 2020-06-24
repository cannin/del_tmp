```
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<sbgn xmlns="http://sbgn.org/libsbgn/0.3">
    <map id="map1" language="activity flow">
        <glyph id="glyph0" class="phenotype">
            <label text="Pro-invasion&#xA;migration&#xA;metastasis&#xA;gene expression&#xA;platform"/>
            <bbox x="235.0" y="187.5" w="130.0" h="75.0"/>
        </glyph>
        <glyph id="glyph1" class="biological activity">
            <label text="Metastatic&#xA;suppressor&#xA;genes&#xA;activity"/>
            <bbox x="246.0" y="380.0" w="108.0" h="60.0"/>
        </glyph>
        <glyph id="glyph2" class="biological activity">
            <label text="TGF beta"/>
            <bbox x="246.0" y="5.0" w="108.0" h="60.0"/>
        </glyph>
        <glyph id="glyph3" class="biological activity">
            <label text="Mutant p53/&#xA;P-Smad"/>
            <bbox x="6.0" y="205.0" w="108.0" h="60.0"/>
        </glyph>
        <glyph id="glyph4" class="biological activity">
            <label text="p63"/>
            <bbox x="6.0" y="380.0" w="108.0" h="60.0"/>
        </glyph>
        <glyph id="glyph5" class="biological activity">
            <label text="Ras"/>
            <bbox x="4.0" y="5.0" w="72.0" h="40.0"/>
        </glyph>
        <glyph id="glyph6" class="and" orientation="vertical">
            <bbox x="39.0" y="124.0" w="42.0" h="42.0"/>
            <port id="glyph6.1" x="60.0" y="103.0"/>
            <port id="glyph6.2" x="60.0" y="187.0"/>
        </glyph>
        <arc id="arc0" class="positive influence" source="glyph2" target="glyph0">
            <start x="300.0" y="65.0"/>
            <end x="300.0" y="187.5"/>
        </arc>
        <arc id="arc1" class="positive influence" source="glyph6.2" target="glyph3">
            <start x="60.0" y="187.0"/>
            <end x="60.0" y="205.0"/>
        </arc>
        <arc id="arc2" class="necessary stimulation" source="glyph4" target="glyph1">
            <start x="114.0" y="410.0"/>
            <end x="246.0" y="410.0"/>
        </arc>
        <arc id="arc3" class="logic arc" source="glyph5" target="glyph6.1">
            <start x="45.0" y="45.0"/>
            <end x="60.0" y="103.0"/>
        </arc>
        <arc id="arc4" class="negative influence" source="glyph3" target="glyph4">
            <start x="60.0" y="265.0"/>
            <end x="60.0" y="380.0"/>
        </arc>
        <arc id="arc5" class="negative influence" source="glyph1" target="glyph0">
            <start x="300.0" y="380.0"/>
            <end x="300.0" y="262.5"/>
        </arc>
        <arc id="arc6" class="logic arc" source="glyph2" target="glyph6.1">
            <start x="246.0" y="35.0"/>
            <next x="160.0" y="35.0"/>
            <end x="60.0" y="103.0"/>
        </arc>
    </map>
</sbgn>
```
