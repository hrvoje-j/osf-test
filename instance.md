### OSF instance
| port | ime instance	| deployani branch | mobilna okolina | fiksna okolina | mdm okolina | startan |
| --- | --- | --- | --- | --- | --- | --- |
| 7009 | OSF_TEST       |  sepa      | WPOSPP | compass test |  test  | :heavy_check_mark: |
| 7010 | OSF_1_TEST     |  tbank     | WPOSPP | compass test |  test  | :heavy_check_mark: |
| 7011 | OSF_2_TEST     |legal_representative| WPOSPP | compass test |  test  | :heavy_check_mark: |
| 7012 | OSF_3_TEST     |trajni_nalog| WPOSPP | compass test |  test  | :heavy_check_mark: |
| 7013 | OSF_4_TEST     |McKinseyV2  | WPOSPP | compass test |  test  | :heavy_check_mark: |
| 7039 | OSF_VPN_TEST   |vpn_admin   | WPOSPP | compass test |  test  | :heavy_check_mark: |
| 7059 | OSF_VPN_TEST_2 |  titan     | WPOSPP | compass test |  test  | :heavy_check_mark: |

### Branchevi
| branch | opis | razvoj | test |
| --- | --- | --- | --- |
| master | ono što je trenutno na produkciji ili bugfiksevi koji idu na produkciju u sljedećem deployu | | |
| sepa | sepa | zoran | darko |
| tbank | tbank | vuglec | darko/domagoj |
| legal_representative | ovlaštena osoba | vuglec | domagoj |
| McKinseyV2 | McKinsey nadogradnja preporuka  | vuglec | darko |
| trajni_nalog | maknuta opcija korisnik ce sam do banke | vuglec | darko |
| titan | titan faza 2, merge ponuda | zoran/hrvoje | bojan |



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
