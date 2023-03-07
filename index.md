### Robust Feature Decoupling in Voice Conversion by using Locality-Based Instance Normalization
### Compared with other methods
#### VCTK
1. F2F, We have always maintained that we would never abandon Scottish football.
2. F2M, These take the shape of a long round arch, with its path high above, and its two ends apparently beyond the horizon.
3. M2F, She can scoop these things into three red bags, and we will go meet her Wednesday at the train station.
4. M2M, The actual primary rainbow observed is said to be the effect of super-imposition of a number of bows. 

<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>ADAINVC</td>
      <td>ADAINVC_LoIN</td>
      <td>AGAINVC</td>
      <td>AGAINVC_LoIN</td>
      <td>MediumVC</td>
      <td>MediumVC_LoIN</td>
      <td>MAE-VC</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCTK/F2F/1/p276_142.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCTK/F2F/1/p303_088.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCTK/F2F/1/ADAINVC_p276_142TOp303_088.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCTK/F2F/1/ADAINVC_loIN_p276_142TOp303_088.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCTK/F2F/1/AGAINVC_p276_142TOp303_088.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCTK/F2F/1/AGAINVC_loIN_p276_142TOp303_088.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/F2F/1/MediumVC_p276_142TOp303_088.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/F2F/1/MediumVC_LoIN_p276_142TOp303_088.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCTK/F2M/1/p240_008.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCTK/F2M/1/p374_001.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCTK/F2M/1/ADAINVC_p240_008TOp374_001.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCTK/F2M/1/ADAINVC_loIN_p240_008TOp374_001.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCTK/F2M/1/AGAINVC_p240_008TOp374_001.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCTK/F2M/1/AGAINVC_loIN_p240_008TOp374_001.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/F2M/1/MediumVC_p240_008TOp374_001.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/F2M/1/MediumVC_LoIN_p240_008TOp374_001.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCTK/M2F/1/p232_005.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCTK/M2F/1/p308_329.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCTK/M2F/1/ADAINVC_p232_005TOp308_329.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCTK/M2F/1/ADAINVC_loIN_p232_005TOp308_329.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCTK/M2F/1/AGAINVC_p232_005TOp308_329.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCTK/M2F/1/AGAINVC_loIN_p232_005TOp308_329.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/M2F/1/MediumVC_p232_005TOp308_329.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/M2F/1/MediumVC_LoIN_p232_005TOp308_329.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCTK/M2M/1/p246_022.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCTK/M2M/1/p245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCTK/M2M/1/ADAINVC_p246_022TOp245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCTK/M2M/1/ADAINVC_loIN_p246_022TOp245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCTK/M2M/1/AGAINVC_p246_022TOp245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCTK/M2M/1/AGAINVC_loIN_p246_022TOp245_093.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/M2M/1/MediumVC_p246_022TOp245_093.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCTK/M2M/1/MediumVC_LoIN_p246_022TOp245_093.wav"> </audio></td>
   </tr>
   
</table>

#### VCC2020
1. F2F, Their solution requires development of the human  capacity for social interest.
2. F2M, Not all Wall Street professionals dismiss dividends.
3. M2F, There is a connection between all of this.
4. M2M, Initial Wall Street enthusiasm has surprised even privatization advocates.

<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>ADAINVC</td>
      <td>ADAINVC_LoIN</td>
      <td>AGAINVC</td>
      <td>AGAINVC_LoIN</td>
      <td>MediumVC</td>
      <td>MediumVC_LoIN</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCC/F2F/1/SEF1_E10054.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCC/F2F/1/SEF2_E10028.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCC/F2F/1/ADAINVC_SEF2_E10028TOSEF1_E10054.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCC/F2F/1/ADAINVC_loIN_SEF2_E10028TOSEF1_E10054.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCC/F2F/1/AGAINVC_SEF2_E10028TOSEF1_E10054.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCC/F2F/1/AGAINVC_loIN_SEF2_E10028TOSEF1_E10054.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/F2F/1/MediumVC_SEF2_E10028TOSEF1_E10054.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/F2F/1/MediumVC_LoIN_SEF2_E10028TOSEF1_E10054.wav"> </audio></td>
     
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCC/F2M/1/TEF1_E20033.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCC/F2M/1/TEM2_E20017.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCC/F2M/1/ADAINVC_TEF1_E20033TOTEM2_E20017.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCC/F2M/1/ADAINVC_loIN_TEF1_E20033TOTEM2_E20017.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCC/F2M/1/AGAINVC_TEF1_E20033TOTEM2_E20017.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCC/F2M/1/AGAINVC_loIN_TEF1_E20033TOTEM2_E20017.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/F2M/1/MediumVC_TEF1_E20033TOTEM2_E20017.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/F2M/1/MediumVC_LoIN_TEF1_E20033TOTEM2_E20017.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCC/M2F/1/SEM1_E10012.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCC/M2F/1/TEF2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCC/M2F/1/ADAINVC_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCC/M2F/1/ADAINVC_loIN_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCC/M2F/1/AGAINVC_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCC/M2F/1/AGAINVC_loIN_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/M2F/1/MediumVC_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/M2F/1/MediumVC_LoIN_SEM1_E10012TOTEF2_E10056.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/VCC/M2M/1/TEM1_E20038.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/VCC/M2M/1/SEM2_E10066.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/VCC/M2M/1/ADAINVC_TEM1_E20038TOSEM2_E10066.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/VCC/M2M/1/ADAINVC_loIN_TEM1_E20038TOSEM2_E10066.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/VCC/M2M/1/AGAINVC_TEM1_E20038TOSEM2_E10066.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/VCC/M2M/1/AGAINVC_loIN_TEM1_E20038TOSEM2_E10066.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/M2M/1/MediumVC_TEM1_E20038TOSEM2_E10066.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/VCC/M2M/1/MediumVC_LoIN_TEM1_E20038TOSEM2_E10066.wav"> </audio></td>
   </tr>
   
</table>

#### LibriSpeech
1. F2F, Just before the noon meal Keith appeared once more at the kitchen door.
2. F2M, In India it is usually made with chicken, but any kind of meat does nicely.
3. M2F, All this against which he now inveighed so bitterly was but a necessary stage in the shaping of his odd destiny.
4. M2M, And the subordinate care of justice and the revenue was delegated to seven consulars, three correctors, and five presidents, who governed the fifteen regions of Italy according to the principles, and even the forms, of Roman jurisprudence.
<table>
   <tr>
      <td>Source</td>
      <td>Target</td>
      <td>ADAINVC</td>
      <td>ADAINVC_LoIN</td>
      <td>AGAINVC</td>
      <td>AGAINVC_LoIN</td>
      <td>MediumVC</td>
      <td>MediumVC_LoIN</td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/LibriSpeech/F2F/1/5984_63095_000047_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/LibriSpeech/F2F/1/6904_262305_000036_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/LibriSpeech/F2F/1/ADAINVC_5984_63095_000047_000000TO6904_262305_000036_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/LibriSpeech/F2F/1/ADAINVC_loIN_5984_63095_000047_000000TO6904_262305_000036_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/LibriSpeech/F2F/1/AGAINVC_5984_63095_000047_000000TO6904_262305_000036_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/LibriSpeech/F2F/1/AGAINVC_loIN_5984_63095_000047_000000TO6904_262305_000036_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/F2F/1/MediumVC_5984_63095_000047_000000TO6904_262305_000036_000000.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/F2F/1/MediumVC_LoIN_5984_63095_000047_000000TO6904_262305_000036_000000.wav"> </audio></td>
     
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/LibriSpeech/F2M/1/1335_163935_000019_000004.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/LibriSpeech/F2M/1/8011_280922_000015_000006.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/LibriSpeech/F2M/1/ADAINVC_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/LibriSpeech/F2M/1/ADAINVC_loIN_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/LibriSpeech/F2M/1/AGAINVC_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/LibriSpeech/F2M/1/AGAINVC_loIN_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/F2M/1/MediumVC_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/F2M/1/MediumVC_loIN_1335_163935_000019_000004TO8011_280922_000015_000006.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/LibriSpeech/M2F/1/1283_129808_000043_000001.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/LibriSpeech/M2F/1/2254_152831_000004_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/LibriSpeech/M2F/1/ADAINVC_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/LibriSpeech/M2F/1/ADAINVC_loIN_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/LibriSpeech/M2F/1/AGAINVC_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/LibriSpeech/M2F/1/AGAINVC_loIN_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/M2F/1/MediumVC_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/M2F/1/MediumVC_loIN_1283_129808_000043_000001TO2254_152831_000004_000000.wav"> </audio></td>
   </tr>
   <tr>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_s" src="samples/LibriSpeech/M2M/1/1874_143361_000011_000007.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_t" src="samples/LibriSpeech/M2M/1/4243_14929_000012_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_A" src="samples/LibriSpeech/M2M/1/ADAINVC_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_B" src="samples/LibriSpeech/M2M/1/ADAINVC_loIN_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_C" src="samples/LibriSpeech/M2M/1/AGAINVC_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_D" src="samples/LibriSpeech/M2M/1/AGAINVC_loIN_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
      <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/M2M/1/MediumVC_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
     <td><audio id="audio" controls="" preload="none"> <source id="V1_E" src="samples/LibriSpeech/M2M/1/MediumVC_LoIN_1874_143361_000011_000007TO4243_14929_000012_000000.wav"> </audio></td>
   </tr>
   
</table>
