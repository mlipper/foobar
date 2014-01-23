**Example Address Requests:**

    /v1/address.json?houseNumber=314&street=west 100 st&borough=manhattan&app_id=abc123&app_key=def456
    /v1/address.xml?houseNumber=109-20&street=71st rd&borough=queens&app_id=abc123&app_key=def456
  
**Example JSON Response**

```json
{
  "address": {
    "assemblyDistrict": "69",
    "bbl": "1018887502",
    "bblBoroughCode": "1",
    "bblTaxBlock": "01888",
    "bblTaxLot": "7502",
    "boeLgcPointer": "1",
    "boePreferredStreetName": "WEST  100 STREET",
    "boePreferredstreetCode": "13577001",
    "boroughCode1In": "1",
    "buildingIdentificationNumber": "1057093",
    "censusBlock2000": "6000",
    "censusBlock2010": "2000",
    "censusTract1990": "187",
    "censusTract2000": "187",
    "censusTract2010": "187",
    "cityCouncilDistrict": "09",
    "civilCourtDistrict": "05",
    "coincidenceSegmentCount": "1",
    "communityDistrict": "107",
    "communityDistrictBoroughCode": "1",
    "communityDistrictNumber": "07",
    "communitySchoolDistrict": "03",
    "condominiumBillingBbl": "1018887502",
    "condominiumFlag": "C",
    "congressionalDistrict": "10",
    "cooperativeIdNumber": "0000",
    "crossStreetNamesFlagIn": "E",
    "dcpPreferredLgc": "01",
    "dofCondominiumIdentificationNumber": "1981",
    "dotStreetLightContractorArea": "1",
    "dynamicBlock": "601",
    "electionDistrict": "049",
    "fireBattalion": "11",
    "fireCompanyNumber": "022",
    "fireCompanyType": "L",
    "fireDivision": "03",
    "firstBoroughName": "MANHATTAN",
    "firstStreetCode": "13577001010",
    "firstStreetNameNormalized": "WEST  100 STREET",
    "fromLionNodeId": "0023422",
    "fromPreferredLgcsFirstSetOf5": "01",
    "genericId": "0060351",
    "geosupportFunctionCode": "1B",
    "geosupportReturnCode": "00",
    "geosupportReturnCode2": "00",
    "gi5DigitStreetCode1": "35770",
    "giBoroughCode1": "1",
    "giBuildingIdentificationNumber1": "1057093",
    "giDcpPreferredLgc1": "01",
    "giHighHouseNumber1": "316",
    "giLowHouseNumber1": "314",
    "giSideOfStreetIndicator1": "L",
    "giStreetCode1": "13577001",
    "giStreetName1": "WEST  100 STREET",
    "healthArea": "3110",
    "healthCenterDistrict": "16",
    "highBblOfThisBuildingsCondominiumUnits": "1018881233",
    "highCrossStreetB5SC1": "129690",
    "highCrossStreetCode1": "12969001",
    "highCrossStreetName1": "RIVERSIDE DRIVE",
    "highHouseNumberOfBlockfaceSortFormat": "000398000AA",
    "houseNumber": "314",
    "houseNumberIn": "314",
    "houseNumberSortFormat": "000314000AA",
    "interimAssistanceEligibilityIndicator": "I",
    "internalLabelXCoordinate": "0991892",
    "internalLabelYCoordinate": "0230017",
    "legacySegmentId": "0037349",
    "lionKeyBoroughCode": "1",
    "lionKeyFaceCode": "5345",
    "lionKeyForVanityAddressBoroughCode": "1",
    "lionKeyForVanityAddressFaceCode": "5345",
    "lionKeyForVanityAddressSequenceNumber": "00060",
    "lionKeySequenceNumber": "00060",
    "listOf4Lgcs": "01",
    "lowBblOfThisBuildingsCondominiumUnits": "1018881201",
    "lowCrossStreetB5SC1": "144990",
    "lowCrossStreetCode1": "14499001",
    "lowCrossStreetName1": "WEST END AVENUE",
    "lowHouseNumberOfBlockfaceSortFormat": "000300000AA",
    "lowHouseNumberOfDefiningAddressRange": "000314000AA",
    "nta": "MN12",
    "ntaName": "Upper West Side",
    "numberOfCrossStreetB5SCsHighAddressEnd": "1",
    "numberOfCrossStreetB5SCsLowAddressEnd": "1",
    "numberOfCrossStreetsHighAddressEnd": "1",
    "numberOfCrossStreetsLowAddressEnd": "1",
    "numberOfEntriesInListOfGeographicIdentifiers": "0001",
    "numberOfExistingStructuresOnLot": "0001",
    "numberOfStreetFrontagesOfLot": "01",
    "physicalId": "0069454",
    "policePatrolBoroughCommand": "2",
    "policePrecinct": "024",
    "returnCode1a": "00",
    "returnCode1e": "00",
    "roadwayType": "1",
    "rpadBuildingClassificationCode": "R4",
    "rpadSelfCheckCodeForBbl": "5",
    "sanbornBoroughCode": "1",
    "sanbornPageNumber": "034",
    "sanbornVolumeNumber": "07",
    "sanbornVolumeNumberSuffix": "S",
    "sanitationCollectionSchedulingSectionAndSubsection": "5B",
    "sanitationDistrict": "107",
    "sanitationRecyclingCollectionSchedule": "ET",
    "sanitationRegularCollectionSchedule": "TTHS",
    "sanitationSnowPriorityCode": "P",
    "segmentAzimuth": "151",
    "segmentIdentifier": "0037349",
    "segmentLengthInFeet": "00574",
    "segmentOrientation": "W",
    "segmentTypeCode": "U",
    "selfCheckCodeOfBillingBbl": "5",
    "sideOfStreetIndicator": "L",
    "sideOfStreetOfVanityAddress": "L",
    "splitLowHouseNumber": "000300000AA",
    "stateSenatorialDistrict": "31",
    "streetName1In": "west 100 st",
    "streetStatus": "2",
    "taxMapNumberSectionAndVolume": "10703",
    "toLionNodeId": "0023852",
    "toPreferredLgcsFirstSetOf5": "01",
    "trafficDirection": "A",
    "underlyingstreetCode": "13577001",
    "workAreaFormatIndicatorIn": "C",
    "xCoordinate": "0992059",
    "xCoordinateHighAddressEnd": "0991683",
    "xCoordinateLowAddressEnd": "0992186",
    "xCoordinateOfCenterofCurvature": "0000000",
    "yCoordinate": "0230011",
    "yCoordinateHighAddressEnd": "0230221",
    "yCoordinateLowAddressEnd": "0229944",
    "yCoordinateOfCenterofCurvature": "0000000",
    "zipCode": "10025"
  }
}
```

**Example XML Response**

```xml
<geosupportResponse>
  <address>
    <assemblyDistrict>28</assemblyDistrict>
    <attributeBytes>H</attributeBytes>
    <bbl>4022250006</bbl>
    <bblBoroughCode>4</bblBoroughCode>
    <bblTaxBlock>02225</bblTaxBlock>
    <bblTaxLot>0006</bblTaxLot>
    <boeLgcPointer>1</boeLgcPointer>
    <boePreferredStreetName>71 ROAD</boePreferredStreetName>
    <boePreferredstreetCode>41504001</boePreferredstreetCode>
    <boroughCode1In>4</boroughCode1In>
    <buildingIdentificationNumber>4052426</buildingIdentificationNumber>
    <censusBlock2000>4005</censusBlock2000>
    <censusBlock2010>5001</censusBlock2010>
    <censusTract1990>739</censusTract1990>
    <censusTract2000>739</censusTract2000>
    <censusTract2010>739</censusTract2010>
    <cityCouncilDistrict>29</cityCouncilDistrict>
    <civilCourtDistrict>04</civilCourtDistrict>
    <coincidenceSegmentCount>1</coincidenceSegmentCount>
    <communityDistrict>406</communityDistrict>
    <communityDistrictBoroughCode>4</communityDistrictBoroughCode>
    <communityDistrictNumber>06</communityDistrictNumber>
    <communitySchoolDistrict>28</communitySchoolDistrict>
    <condominiumBillingBbl>0000000000</condominiumBillingBbl>
    <congressionalDistrict>06</congressionalDistrict>
    <cooperativeIdNumber>0000</cooperativeIdNumber>
    <cornerCode>SE</cornerCode>
    <crossStreetNamesFlagIn>E</crossStreetNamesFlagIn>
    <dcpPreferredLgc>01</dcpPreferredLgc>
    <dotStreetLightContractorArea>4</dotStreetLightContractorArea>
    <dynamicBlock>410</dynamicBlock>
    <electionDistrict>029</electionDistrict>
    <fireBattalion>50</fireBattalion>
    <fireCompanyNumber>151</fireCompanyNumber>
    <fireCompanyType>L</fireCompanyType>
    <fireDivision>13</fireDivision>
    <firstBoroughName>QUEENS</firstBoroughName>
    <firstStreetCode>41504001010</firstStreetCode>
    <firstStreetNameNormalized>71 ROAD</firstStreetNameNormalized>
    <fromLionNodeId>0067082</fromLionNodeId>
    <genericId>0070010</genericId>
    <geosupportFunctionCode>1B</geosupportFunctionCode>
    <geosupportReturnCode>00</geosupportReturnCode>
    <geosupportReturnCode2>00</geosupportReturnCode2>
    <gi5DigitStreetCode1>15040</gi5DigitStreetCode1>
    <gi5DigitStreetCode2>59990</gi5DigitStreetCode2>
    <giBoroughCode1>4</giBoroughCode1>
    <giBoroughCode2>4</giBoroughCode2>
    <giBuildingIdentificationNumber1>4052426</giBuildingIdentificationNumber1>
    <giBuildingIdentificationNumber2>4052426</giBuildingIdentificationNumber2>
    <giDcpPreferredLgc1>01</giDcpPreferredLgc1>
    <giDcpPreferredLgc2>01</giDcpPreferredLgc2>
    <giHighHouseNumber1>109-20</giHighHouseNumber1>
    <giHighHouseNumber2>109-05</giHighHouseNumber2>
    <giLowHouseNumber1>109-06</giLowHouseNumber1>
    <giLowHouseNumber2>109-05</giLowHouseNumber2>
    <giSideOfStreetIndicator1>R</giSideOfStreetIndicator1>
    <giSideOfStreetIndicator2>L</giSideOfStreetIndicator2>
    <giStreetCode1>41504001</giStreetCode1>
    <giStreetCode2>45999001</giStreetCode2>
    <giStreetName1>71 ROAD</giStreetName1>
    <giStreetName2>QUEENS BOULEVARD</giStreetName2>
    <healthArea>1920</healthArea>
    <healthCenterDistrict>46</healthCenterDistrict>
    <highBblOfThisBuildingsCondominiumUnits>4022250006</highBblOfThisBuildingsCondominiumUnits>
    <highCrossStreetB5SC1>420390</highCrossStreetB5SC1>
    <highCrossStreetCode1>42039001</highCrossStreetCode1>
    <highCrossStreetName1>110 STREET</highCrossStreetName1>
    <highHouseNumberOfBlockfaceSortFormat>100109098AA</highHouseNumberOfBlockfaceSortFormat>
    <houseNumber>109-20</houseNumber>
    <houseNumberIn>109-20</houseNumberIn>
    <houseNumberSortFormat>100109020AA</houseNumberSortFormat>
    <interimAssistanceEligibilityIndicator>I</interimAssistanceEligibilityIndicator>
    <internalLabelXCoordinate>1028016</internalLabelXCoordinate>
    <internalLabelYCoordinate>0202046</internalLabelYCoordinate>
    <legacySegmentId>0113813</legacySegmentId>
    <lionKeyBoroughCode>4</lionKeyBoroughCode>
    <lionKeyFaceCode>5820</lionKeyFaceCode>
    <lionKeyForVanityAddressBoroughCode>4</lionKeyForVanityAddressBoroughCode>
    <lionKeyForVanityAddressFaceCode>5820</lionKeyForVanityAddressFaceCode>
    <lionKeyForVanityAddressSequenceNumber>02020</lionKeyForVanityAddressSequenceNumber>
    <lionKeySequenceNumber>02020</lionKeySequenceNumber>
    <listOf4Lgcs>01</listOf4Lgcs>
    <lowBblOfThisBuildingsCondominiumUnits>4022250006</lowBblOfThisBuildingsCondominiumUnits>
    <lowCrossStreetB5SC1>435780</lowCrossStreetB5SC1>
    <lowCrossStreetCode1>435780</lowCrossStreetCode1>
    <lowCrossStreetName1>BEND</lowCrossStreetName1>
    <lowHouseNumberOfBlockfaceSortFormat>100109000AA</lowHouseNumberOfBlockfaceSortFormat>
    <lowHouseNumberOfDefiningAddressRange>100109006AA</lowHouseNumberOfDefiningAddressRange>
    <nta>QN17</nta>
    <ntaName>Forest Hills</ntaName>
    <numberOfCrossStreetB5SCsHighAddressEnd>1</numberOfCrossStreetB5SCsHighAddressEnd>
    <numberOfCrossStreetB5SCsLowAddressEnd>1</numberOfCrossStreetB5SCsLowAddressEnd>
    <numberOfCrossStreetsHighAddressEnd>1</numberOfCrossStreetsHighAddressEnd>
    <numberOfCrossStreetsLowAddressEnd>1</numberOfCrossStreetsLowAddressEnd>
    <numberOfEntriesInListOfGeographicIdentifiers>0002</numberOfEntriesInListOfGeographicIdentifiers>
    <numberOfExistingStructuresOnLot>0001</numberOfExistingStructuresOnLot>
    <numberOfStreetFrontagesOfLot>02</numberOfStreetFrontagesOfLot>
    <physicalId>0080824</physicalId>
    <policePatrolBoroughCommand>6</policePatrolBoroughCommand>
    <policePrecinct>112</policePrecinct>
    <returnCode1a>00</returnCode1a>
    <returnCode1e>00</returnCode1e>
    <roadwayType>1</roadwayType>
    <rpadBuildingClassificationCode>D1</rpadBuildingClassificationCode>
    <rpadSelfCheckCodeForBbl>8</rpadSelfCheckCodeForBbl>
    <sanbornBoroughCode>4</sanbornBoroughCode>
    <sanbornPageNumber>066</sanbornPageNumber>
    <sanbornVolumeNumber>19</sanbornVolumeNumber>
    <sanitationCollectionSchedulingSectionAndSubsection>1E</sanitationCollectionSchedulingSectionAndSubsection>
    <sanitationDistrict>406</sanitationDistrict>
    <sanitationRecyclingCollectionSchedule>EW</sanitationRecyclingCollectionSchedule>
    <sanitationRegularCollectionSchedule>WS</sanitationRegularCollectionSchedule>
    <sanitationSnowPriorityCode>P</sanitationSnowPriorityCode>
    <segmentAzimuth>021</segmentAzimuth>
    <segmentIdentifier>0113813</segmentIdentifier>
    <segmentLengthInFeet>00455</segmentLengthInFeet>
    <segmentOrientation>1</segmentOrientation>
    <segmentTypeCode>U</segmentTypeCode>
    <sideOfStreetIndicator>R</sideOfStreetIndicator>
    <sideOfStreetOfVanityAddress>R</sideOfStreetOfVanityAddress>
    <splitLowHouseNumber>100109000AA</splitLowHouseNumber>
    <stateSenatorialDistrict>16</stateSenatorialDistrict>
    <streetAttributeIndicator>H</streetAttributeIndicator>
    <streetName1In>71st rd</streetName1In>
    <streetStatus>2</streetStatus>
    <taxMapNumberSectionAndVolume>41204</taxMapNumberSectionAndVolume>
    <toLionNodeId>0050496</toLionNodeId>
    <toPreferredLgcsFirstSetOf5>01</toPreferredLgcsFirstSetOf5>
    <trafficDirection>A</trafficDirection>
    <underlyingstreetCode>41504001</underlyingstreetCode>
    <workAreaFormatIndicatorIn>C</workAreaFormatIndicatorIn>
    <xCoordinate>1027969</xCoordinate>
    <xCoordinateHighAddressEnd>1028268</xCoordinateHighAddressEnd>
    <xCoordinateLowAddressEnd>1027844</xCoordinateLowAddressEnd>
    <xCoordinateOfCenterofCurvature>0000000</xCoordinateOfCenterofCurvature>
    <yCoordinate>0202112</yCoordinate>
    <yCoordinateHighAddressEnd>0202233</yCoordinateHighAddressEnd>
    <yCoordinateLowAddressEnd>0202066</yCoordinateLowAddressEnd>
    <yCoordinateOfCenterofCurvature>0000000</yCoordinateOfCenterofCurvature>
    <zipCode>11375</zipCode>
  </address>
</geosupportResponse>
```

### Etc.