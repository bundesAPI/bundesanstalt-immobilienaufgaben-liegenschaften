# bundesanstalt-immobilienaufgaben-liegenschaften

| File                            | Info                                           | Comment                                                                                              |
|---------------------------------|------------------------------------------------|------------------------------------------------------------------------------------------------------|
| Anlage_wo_pwd.pdf               | raw file                                       |                                                                                                      |
| Anlage_wo_pwd.tsv               | Same as Anlage_wo_pwd.pdf but extracted as tsv | [with pdf2json](https://github.com/bundesAPI/bundesanstalt-immobilienaufgaben-liegenschaften/pull/1) |
| Fixed_Anlage_wo_pwd.csv         | cleaned up data garbage                        | with [fix_postcode_city_mix.ipynb](fix_postcode_city_mix.ipynb)                                      |
| Fixed_Anlage_wo_pwd_Encoded.csv | geo-encoded data                               | with osm<br/>Exact_Pos_Failed means that City+Zip+Street was not found but City+Zip                  |

<p align="center">
<img width="350px" src="liegenschaften.png" />
</p>