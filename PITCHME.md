---?color=#000000

# CityGML 건물 `GML` 예제 파일

---
```XML
<CityModel xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://www.opengis.net/citygml/2.0" xmlns:xAL="urn:oasis:names:tc:ciq:xsdschema:xAL:2.0"
    xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:gml="http://www.opengis.net/gml" xmlns:dem="http://www.opengis.net/citygml/relief/2.0"
    xmlns:bldg="http://www.opengis.net/citygml/building/2.0" xsi:schemaLocation="http://www.opengis.net/citygml/building/2.0 http://schemas.opengis.net/citygml/building/2.0/building.xsd http://www.opengis.net/citygml/relief/2.0 http://schemas.opengis.net/citygml/relief/2.0/relief.xsd">
    <gml:name>Simple 3D city model LOD3 without Appearance</gml:name>
    <gml:boundedBy>
        <gml:Envelope srsDimension="3" srsName="urn:ogc:def:crs,crs:EPSG::25832,crs:EPSG::5783">
            <gml:lowerCorner>458868.0 5438343.0 112.0</gml:lowerCorner>
            <gml:upperCorner>458892.0 5438362.0 117.0</gml:upperCorner>
        </gml:Envelope>
    </gml:boundedBy>
    <cityObjectMember>
        <bldg:Building gml:id="GML_7b1a5a6f-ddad-4c3d-a507-3eb9ee0a8e68">
            <gml:name>Example Building LOD3 </gml:name>
            <bldg:function codeSpace="http://www.sig3d.org/codelists/standard/building/2.0/_AbstractBuilding_function.xml">1000</bldg:function>
            <bldg:yearOfConstruction>1985</bldg:yearOfConstruction>
            <bldg:roofType codeSpace="http://www.sig3d.org/codelists/standard/building/2.0/_AbstractBuilding_roofType.xml">1030</bldg:roofType>
            <bldg:measuredHeight uom="#m">5.0</bldg:measuredHeight>
            <bldg:storeysAboveGround>1</bldg:storeysAboveGround>
            <bldg:storeyHeightsAboveGround uom="#m">3.0</bldg:storeyHeightsAboveGround>
             <bldg:boundedBy>
                <bldg:WallSurface>
                    <gml:name>Wall South</gml:name>
                    <bldg:lod3MultiSurface>
                        <gml:MultiSurface>
                            <gml:surfaceMember>
                                <gml:CompositeSurface gml:id="GML_1d350a50-6acc-4d3c-8c28-326ca4305fd1">
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="PolyID10204_1916_571790_369478">
                                            <gml:exterior>
                                                <gml:LinearRing>
                                                    <gml:posList>
                                                        458878.5 5438350 113.2 458878.5 5438350 114.2 458878.5
                                                        5438350.1 114.2 458878.5 5438350.1 113.2 458878.5 5438350 113.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="PolyID10205_105_876837_53833">
                                            <gml:exterior>
                                                <gml:LinearRing>
                                                    <gml:posList>
                                                        458875 5438350 112 458885 5438350 112 458885 5438350 115 458875
                                                        5438350 115 458875 5438350 112
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                            <gml:interior>
                                                <gml:LinearRing>
                                                    <gml:posList>
                                                        458877 5438350 114.2 458878.5 5438350 114.2 458878.5 5438350
                                                        113.2 458877 5438350 113.2 458877 5438350 114.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:interior>
                                            <gml:interior>
                                                <gml:LinearRing>
                                                    <gml:posList>
                                                        458881.5 5438350 114.2 458883 5438350 114.2 458883 5438350
                                                        113.2 458881.5 5438350 113.2 458881.5 5438350 114.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:interior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="PolyID10206_1133_78310_431691">
                                            <gml:exterior>
                                                <gml:LinearRing>
                                                    <gml:posList>
                                                        458881.5 5438350 114.2 458881.5 5438350 113.2 458881.5
                                                        5438350.1 113.2 458881.5 5438350.1 114.2 458881.5 5438350 114.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="PolyID10207_170_321284_424514">
                                            <gml:exterior>
                                                <gml:LinearRing>
                                                    <gml:posList>
                                                        458883 5438350 114.2 458881.5 5438350 114.2 458881.5 5438350.1
                                                        114.2 458883 5438350.1 114.2 458883 5438350 114.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="PolyID10208_1773_608580_43387">
                                            <gml:exterior>
                                                <gml:LinearRing gml:id="PolyID10208_1773_608580_43387_0">
                                                    <gml:posList>
                                                        458878.5 5438350 114.2 458877 5438350 114.2 458877 5438350.1
                                                        114.2 458878.5 5438350.14 114.2 458878.5 5438350 114.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="PolyID10209_1571_771435_238540">
                                            <gml:exterior>
                                                <gml:LinearRing gml:id="PolyID10209_1571_771435_238540_0">
                                                    <gml:posList>
                                                        458881.5 5438350 113.2 458883 5438350 113.2 458883 5438350.1
                                                        113.2 458881.5 5438350.1 113.2 458881.5 5438350 113.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="PolyID10210_599_287520_415766">
                                            <gml:exterior>
                                                <gml:LinearRing gml:id="PolyID10210_599_287520_415766_0">
                                                    <gml:posList>
                                                        458883 5438350 113.2 458883 5438350 114.2 458883 5438350.1
                                                        114.2 458883 5438350.1 113.2 458883 5438350 113.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="PolyID10211_1784_120327_382264">
                                            <gml:exterior>
                                                <gml:LinearRing gml:id="PolyID10211_1784_120327_382264_0">
                                                    <gml:posList>
                                                        458877 5438350 113.2 458878.5 5438350 113.2 458878.5 5438350.1
                                                        113.2 458877 5438350.1 113.2 458877 5438350 113.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="PolyID10212_1143_394036_161326">
                                            <gml:exterior>
                                                <gml:LinearRing gml:id="PolyID10212_1143_394036_161326_0">
                                                    <gml:posList>
                                                        458877 5438350 114.2 458877 5438350 113.2 458877 5438350.1
                                                        113.2 458877 5438350.1 114.2 458877 5438350 114.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                </gml:CompositeSurface>
                            </gml:surfaceMember>
                        </gml:MultiSurface>
                    </bldg:lod3MultiSurface>
                    <bldg:opening>
                        <bldg:Window gml:id="GML_3b09d6a5-4c24-4847-a8a2-e97475e3de47">
                            <gml:name>Window South 1</gml:name>
                            <bldg:lod3MultiSurface>
                                <gml:MultiSurface>
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="GML_5e07e2cc-c28c-480e-880f-dfdfe287bb9e">
                                            <gml:exterior>
                                                <gml:LinearRing gml:id="PolyID10213_1986_38589_374102_0">
                                                    <gml:posList>
                                                        458878.5 5438350.1 114.2 458877 5438350.1 114.2 458877
                                                        5438350.1 113.2 458878.5 5438350.1 113.2 458878.5 5438350.1
                                                        114.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                </gml:MultiSurface>
                            </bldg:lod3MultiSurface>
                        </bldg:Window>
                    </bldg:opening>
                    <bldg:opening>
                        <bldg:Window gml:id="GML_f75f01cc-c584-4a62-b34a-4a0e2640550d">
                            <gml:name>Window South 2</gml:name>
                            <bldg:lod3MultiSurface>
                                <gml:MultiSurface>
                                    <gml:surfaceMember>
                                        <gml:Polygon gml:id="GML_d0ea2b6b-7992-4284-9a20-957a6c5c1cea">
                                            <gml:exterior>
                                                <gml:LinearRing gml:id="PolyID10214_1496_142050_398240_0">
                                                    <gml:posList>
                                                        458883 5438350.1 114.2 458881.5 5438350.1 114.2 458881.5
                                                        5438350.1 113.2 458883 5438350.1 113.2 458883 5438350.1 114.2
                                                    </gml:posList>
                                                </gml:LinearRing>
                                            </gml:exterior>
                                        </gml:Polygon>
                                    </gml:surfaceMember>
                                </gml:MultiSurface>
                            </bldg:lod3MultiSurface>
                        </bldg:Window>
                    </bldg:opening>
                </bldg:WallSurface>
            </bldg:boundedBy>
            <bldg:boundedBy>
                <bldg:RoofSurface>
                    <gml:name>Roof North</gml:name>
                    <bldg:lod3MultiSurface>
                        <gml:MultiSurface>
                            <!--  Roof slab  -->
                            <gml:surfaceMember>
                                <gml:Polygon gml:id="GML_ec6a8966-58d9-4894-8edd-9aceb91b923f">
                                    <gml:exterior>
                                        <gml:LinearRing>
                                            <gml:posList srsDimension="3">
                                                458885 5438355 115 458875 5438355 115 458875 5438352.5 117 458885
                                                5438352.5 117 458885 5438355 115
                                            </gml:posList>
                                        </gml:LinearRing>
                                    </gml:exterior>
                                </gml:Polygon>
                            </gml:surfaceMember>
                            <!--  Roof overhanging  -->
                            <gml:surfaceMember>
                                <gml:Polygon gml:id="GML_70fa738e-80a4-4774-8a3b-322f037fa482">
                                    <gml:exterior>
                                        <gml:LinearRing>
                                            <gml:posList>
                                                458874.6 5438352.5 117 458875 5438352.5 117 458875 5438355 115 458885
                                                5438355 115 458885 5438352.5 117 458885.4 5438352.5 117 458885.4
                                                5438355.312347524 114.75012198097823 458874.6 5438355.312347524
                                                114.75012198097823 458874.6 5438352.5 117
                                            </gml:posList>
                                        </gml:LinearRing>
                                    </gml:exterior>
                                </gml:Polygon>
                            </gml:surfaceMember>
                        </gml:MultiSurface>
                    </bldg:lod3MultiSurface>
                </bldg:RoofSurface>
            </bldg:boundedBy>
            <bldg:lod3Solid>
                <gml:Solid>
                    <gml:exterior>
                        <gml:CompositeSurface>
                            <!--  Wall South  -->
                            <gml:surfaceMember xlink:href="#GML_1d350a50-6acc-4d3c-8c28-326ca4305fd1" />
                            <!--  Roof North  -->
                            <gml:surfaceMember xlink:href="#GML_ec6a8966-58d9-4894-8edd-9aceb91b923f" />
                        </gml:CompositeSurface>
                    </gml:exterior>
                </gml:Solid>
            </bldg:lod3Solid>
            <bldg:address>
                <Address>
                    <xalAddress>
                        <xAL:AddressDetails>
                            <xAL:Country>
                                <xAL:CountryName>Germany</xAL:CountryName>
                                <xAL:Locality Type="Town">
                                    <xAL:LocalityName>Eggenstein-Leopoldshafen</xAL:LocalityName>
                                    <xAL:Thoroughfare Type="Street">
                                        <xAL:ThoroughfareNumber>1</xAL:ThoroughfareNumber>
                                        <xAL:ThoroughfareName>Hermann-von-Helmholtz-Platz</xAL:ThoroughfareName>
                                    </xAL:Thoroughfare>
                                    <xAL:PostalCode>
                                        <xAL:PostalCodeNumber>76344</xAL:PostalCodeNumber>
                                    </xAL:PostalCode>
                                </xAL:Locality>
                            </xAL:Country>
                        </xAL:AddressDetails>
                    </xalAddress>
                    <multiPoint>
                        <gml:MultiPoint>
                            <gml:pointMember>
                                <gml:Point>
                                    <gml:pos srsDimension="3">458880.0 5438352.6 112.0 </gml:pos>
                                </gml:Point>
                            </gml:pointMember>
                        </gml:MultiPoint>
                    </multiPoint>
                </Address>
            </bldg:address>
        </bldg:Building>
    </cityObjectMember>
</CityModel>
```
