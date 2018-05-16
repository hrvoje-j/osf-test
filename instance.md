### OSF instance
| port | ime instance	| deployani branch | mobilna okolina | fiksna okolina | mdm okolina | startan |
| --- | --- | --- | --- | --- | --- | --- |
| 7009 | OCV_TEST |	master | WPOSPP | compass test   |  test  | :heavy_check_mark: |
| 7019 | OCV_TEST_2 | dospijece_placanja | WPOSPP | compass test | test | :x: |
| 7029 | OCV_TEST_3 | setup_modul | WPOSPP | compass test | test | :x: |
| 7039 | OCV_TEST_4 |  | WPOSPP | compass test | test | :x: |
| 7049 | OCV_TEST_5 | master_admin | WPOSPP | compass test | test | :heavy_check_mark: |
| 7059 | OCV_TEST_6 | gdpr | WPOSPP | compass test | test | :heavy_check_mark: |
| 7069 | OCV_TEST_7 | long_tail | WPOSPP | compass test | test | :heavy_check_mark: |
| 7079 (7078 https) | OCV_TEST_8 | new_sales_tool | WPOSPP | compass test | test | :heavy_check_mark: |
| 7089 | OCV_CRM_test | siebel_faza_1 | WPOST2 | ? | ? | :heavy_check_mark: |



### Branchevi
| branch | opis | razvoj | test |
| --- | --- | --- | --- |
| master | ono što je trenutno na produkciji ili bugfiksevi koji idu na produkciju u sljedećem deployu | | |
| steckerleiste  | | hrvoje, vice | |
| temp_canc | privremeno iskljucenje | novotni |  |
| mdmAddressSynchro | uskladivanje mdm dostavne adrese | hrvoje |  |
| biometryPh2 | | novotni | |
| bonus_insurance | | hrvoje | domagoj |
| sepa, sancta_domenica, slavonia, nexTv, multiscreen | | matija | |
| vpn_limit | | hrvoje | balic, bojan |
| new_mdm_contacts | | hrvoje | domagoj |
| sepa_admin | | hrvoje | darko |
| webpos_cache | | hrvoje | balic |
| magenta_tablet | | novotni | darko |
| mudbug, setup_modul | | novotni | darko |
| bus_spec_price | | hrvoje | darko |
| external_policy | | vuglec | domagoj |
| click_and_collect | | | |
| oliver_prepaid | | tonci, andro | |
| skeniranje_poslovni | | vuglec | darko |
| fix_arpu | | hrvoje | |
| mobile_arpu | | hrvoje | |
| dospijece_placanja | | zoran | |
| master_admin | | zoran | |
| gdpr | | novotni | darko |
| new_sales_tool | | novotni | darko |
| siebel_faza_1 | | hrvoje | darko, domagoj |


### Okoline
1. mobilna
 *	WPOSPP - test
 *	WPOST - dev
  *	WPOST2 - crm test

2. fiksna
 * compass test - MasterDataServices:6324
 * acc1 dev - MasterDataServices:7324

3. mdm
 * test - MDMServices:6312/6311
 * dev - MDMServices:5312/5311
 * ? - MDMServices:7312/7311
