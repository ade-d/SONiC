# Media Info Summary Command

New command:
`show interface transceiver *`

Where * can be 'summary' or the specific interface

Examples:
`show interface transceiver summary`
This shows for all interfaces as show below.

`show interface transceiver Ethernet6`
This shows for all Ethernet6.

`show interface transceiver 8`
This shows for all Ethernet8 (8 is a shorthand).

<br>

**Sample Output:**
<br>You may have to scroll horizontally to see all fields.
~~~
Interface    Media Name                      Max Power(W)    Vendor Name    Serial Number    Part Number     QSA        Qualified
                                             Media | Port                                                    Adapter
-----------  ------------------------------  --------------  -------------  ---------------  --------------  ---------  -----------
Ethernet0    QSFP28 100GBASE-CR4-DAC-1.0M    1.5   | 10.0    DELL           CN0APX0081B7PE3  035KG           N/A        Yes
Ethernet8    QSFP28 100GBASE-CR4-DAC-1.0M    1.5   | 10.0    DELL           CN0APX0081B7PE3  035KG           N/A        Yes
Ethernet16   QSFP28 100GBASE-CR4-DAC-1.0M    1.5   | 10.0    DELL           CN07720667Q0010  P7C7N           N/A        Yes
Ethernet24   QSFP28 100GBASE-CR4-DAC-1.0M    1.5   | 10.0    DELL           CN07720667Q0010  P7C7N           N/A        Yes
Ethernet32   QSFP28 100GBASE-CR4-DAC-2.0M    1.5   | 10.0    DELL           CN0LXD009620002  76V43           N/A        Yes
Ethernet40   QSFP28 100GBASE-CR4-DAC-2.0M    1.5   | 10.0    DELL           CN0LXD009620002  76V43           N/A        Yes
Ethernet48   QSFP28 100GBASE-CR4-DAC-3.0M    1.5   | 10.0    DELL           CN0LXD0096I3E2G  3CC35           N/A        Yes
Ethernet56   QSFP28 100GBASE-CR4-DAC-3.0M    1.5   | 10.0    DELL           CN0LXD0096I3E2G  3CC35           N/A        Yes
Ethernet64   QSFP28 100GBASE-CR4-DAC-5.0M    1.5   | 10.0    DELL           CN0LXD009620002  FN4FC           N/A        Yes
Ethernet72   QSFP28 100GBASE-CR4-DAC-5.0M    1.5   | 10.0    DELL           CN0LXD009620002  FN4FC           N/A        Yes
Ethernet80   QSFP28 4x(25GBASE-CR-DAC)-1.0M  1.5   | 10.0    DELL           CN0LXD009610001  26FN3           N/A        Yes
Ethernet88   SFP28 25GBASE-CR-DAC-1.0M       2.5   | 10.0    DELL           CN0LXD009610001  26FN3           Present    Yes
Ethernet96   QSFP28 4x(25GBASE-CR-DAC)-2.0M  1.5   | 10.0    DELL           CN07720683SD0EL  YFNDD           N/A        Yes
Ethernet104  N/A                             N/A   | N/A     N/A            N/A              N/A             N/A        N/A
Ethernet112  QSFP28 4x(25GBASE-CR-DAC)-3.0M  1.5   | 10.0    DELL           CN07720685Q1MNL  7R9N9           N/A        Yes
Ethernet120  SFP28 25GBASE-CR-DAC-3.0M       2.5   | 10.0    DELL           CN07720685Q1MNL  7R9N9           Present    Yes
Ethernet128  QSFP28 100GBASE-SR4             2.5   | 10.0    DELL EMC       CN0F1C009AM000I  14NV5           N/A        Yes
Ethernet136  QSFP28 100GBASE-SR4             3.5   | 10.0    DELL           CN079192823000J  YKMH7           N/A        Yes
Ethernet144  QSFP28 100GBASE-SWDM4           3.5   | 10.0    DELL           MY01360298V00Q3  X7CCC           N/A        Yes
Ethernet152  QSFP28 100GBASE-BIDI            3.5   | 10.0    DELL           CN07919299K01BK  0X9CT           N/A        Yes
Ethernet160  QSFP28 100GBASE-CWDM4           3.5   | 10.0    DELL           MY01360289P001Y  THPF3           N/A        Yes
Ethernet168  QSFP28 100GBASE-LR4             4.5   | 10.0    DELL           CN04829464A0016  GMFC5           N/A        Yes
Ethernet176  QSFP28 100GBASE-FR              4.5   | 10.0    DELL EMC       CN0482949AN0019  PJ62G           N/A        Yes
Ethernet184  QSFP28 100GBASE-BIDI            4.0   | 10.0    DELL EMC       CN04HQ009CDD007  3HKF0           N/A        N/A
Ethernet192  N/A                             N/A   | N/A     N/A            N/A              N/A             N/A        N/A
Ethernet200  N/A                             N/A   | N/A     N/A            N/A              N/A             N/A        N/A
Ethernet208  QSFP56-DD 400GBASE-DR4          14.0* | 10.0    DELLEMC        FD1923AG024      6MGDY           N/A        Yes
Ethernet216  N/A                             N/A   | N/A     N/A            N/A              N/A             N/A        N/A
Ethernet224  QSFP56-DD 400GBASE-SR4.2        14.0* | 10.0    DELL EMC       CN04HQ009CDG002  0059F           N/A        N/A
Ethernet232  N/A                             N/A   | N/A     N/A            N/A              N/A             N/A        N/A
Ethernet240  QSFP56-DD 400GBASE-FR4          10.0  | 10.0    Eoptolink      DK63650001       EOLD-164HG02-6  N/A        N/A
Ethernet248  QSFP56-DD 400GBASE-FR4          10.0  | 10.0    Eoptolink      DK63650002       EOLD-164HG02-6  N/A        N/A
Ethernet256  SFP 1000BASE-T                  1.5   | 2.5     FINISAR CORP.  PTM3BJW          FCLF8522P2BTL   N/A        N/A
Ethernet257  SFP+ 10GBASE-T                  2.0   | 2.5     DELL           16430315         PGYJT           N/A        Yes

~~~

## Explanation of Fields
### Interface
This is the interface, as usual.

<br>

### Media Name
This is a name which provides a succinct summary of the properties of the module, free of version and manufacturer differences.

<br>

### Max Power
This field outlines the **maximum possible** power the media can draw, and the **maximum possible** power the port can provide.
**Note**: the maximum possible power is **not the actual real-time** power. The real-time power is a very dynamic quantity which changes based on load and many factors. However it can never exceed the maximum media power.
We need to display the maximum power so that users are aware of the potential peak of the module. This can prevent damage to the switch and media, when the media power exceeds the port max power.

#### Media Max Power
This is the maximum power the media can ever draw. The actual real time power will always be less than or equal to this value. This max power does not change. It is a fixed value which gives us an idea of what the media can potentially consume.
We need to ensure the media max power does not exceed the port allowed max or we can damage things.
When the media max power exceeds the port max, we shall place an asterisk `*` next to the power value (see `Ethernet208`) to indicate  a possible power overage.

<br>

#### Port Max Power
This is the maximum power a specific port can allow media to draw.
This value may change based on the port, platform, airflow etc. Is it best to never assume what this value is without consulting the manual of the switch.

<br>

#### Vendor, Serial, Part Info
This is as expected. 

#### QSA Adapter
This indicates the presence of a QSA* style adapter. It could be QSA+, or QSA28. We do not specify.

#### Qualified
This indicates if the media is qualified by the vendor of the switch.
**Note**: this field can either be `Yes` or `N/A`. Yes implies certainty, while N/A implies inconclusive.
We allow for inconclusive states because the qualification infrastructure is not yet robust. However if yes is seen, then we are sure it is qualified.
