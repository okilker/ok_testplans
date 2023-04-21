This repository uses a YAML file to generate custom NDcPPv3.0-conformant test plans. 

The generated test plans include the test cases a platform will need to pass in order to be certified under the collaborative Protection Profile for Network Devices Version 3.0 (NDcPPv3.0). These plans are taken from the Network Device Supporting Document Version 3.0 (NDSDv3.0) which defines the Evaluation Activities associated with the Security Functional Requirements (SFR) in the NDcPPv3.0.

### Generate a Custom Test Plan

_You must be logged in to create a new repository._

1. Select **Use this template** button. 
2. Create a new repository with a unique repository name.
2. Check your repository permissions by going to Settings > Actions > General > WorkFlow Permissions > **Read and write permissions**.
3. Click **Save**.
4. Create a branch called `test_branch_1`
5. In the `NDcPPv3.0` directory there are many SFRS:
    ````
    - FAU_GEN_1.adoc
    - FAU_GEN_2.adoc
    - FAU_STG_EXT_1.adoc
    - FCS_CKM_1.adoc
    - FCS_CKM_2.adoc
    - FCS_CKM_4.adoc
    - FCS_COP_1_DataEncryption.adoc
    - FCS_COP_1_Hash.adoc
    - FCS_COP_1_KeyedHash.adoc
    - FCS_COP_1_SigGen.adoc
    - FCS_DTLSC_EXT_1.adoc
    - FCS_RBG_EXT_1.adoc
    - FIA_UIA_EXT_1.adoc
    - FMT_MOF_1_ManualUpdate.adoc
    - MT_MTD_1_CoreData.adoc
    - FMT_SMF_1.adoc
    - FMT_SMR_2.adoc
    - FPT_SKP_EXT_1.adoc
    - FPT_STM_EXT_1.adoc
    - FPT_TST_EXT_1.adoc
    - FPT_TUD_EXT.1.adoc
    - FTA_SSL_3.adoc
    - FTA_SSL_4.adoc
    - FTA_TAB_1.adoc
    - FTP_ITC_1.adoc
    - FTP_TRP_1_Admin.adoc 
    ````
5. Delete any `.adoc` SFRs files you do not want included in your test plan.
6. From the Menu, select the **Actions** button.
7. Select **Combine Asciidoc, Convert to HTML, and Commit** workflow.
7. Select **Run workflow**. You can watch the workflow statusas it runs. 
8. Return to your repository's main page.
9. Download the `combined-testplan.adoc` and/or `testplan.html` documents.
