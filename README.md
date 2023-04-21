This repository uses a YAML file to generate custom NDcPPv3.0 test plans. You must be logged in to create a new repository.
Consider creating a new branch for each custom test plan you want to generate.:

### Generate a Custom Test Plan

1. Select **Use this template** button. 
2. Create a new repository with a unique repository name.
2. Check your repository permissions by going to Settings>Actions>General>WorkFlow Permissions> Read and write permissions.
3. Click **Save**.
4. In the NDcPPv3.0 directory there are many SFRS:
    * FAU_GEN_1.adoc
    * FAU_GEN_2.adoc
    * FAU_STG_EXT_1.adoc
    
    ---

    * FCS_CKM_1.adoc
    * FCS_CKM_2.adoc
    * FCS_CKM_4.adoc
    * FCS_COP_1_DataEncryption.adoc
    * FCS_COP_1_Hash.adoc
    * FCS_COP_1_KeyedHash.adoc
    * FCS_COP_1_SigGen.adoc
    * FCS_DTLSC_EXT_1.adoc
    * FCS_RBG_EXT_1.adoc
    
    ---
    
    * FIA_UIA_EXT_1.adoc
    
    ---
    
    * FMT_MOF_1_ManualUpdate.adoc
    
    ---
    
    * MT_MTD_1_CoreData.adoc
    
    ---
    
    * FMT_SMF_1.adoc
    * FMT_SMR_2.adoc
    
    ---
    
    * FPT_SKP_EXT_1.adoc
    * FPT_STM_EXT_1.adoc
    * FPT_TST_EXT_1.adoc
    * FPT_TUD_EXT.1.adoc
    
    ---
    
    * FTA_SSL_3.adoc
    * FTA_SSL_4.adoc
    * FTA_TAB_1.adoc

    ---

    * FTP_ITC_1.adoc
    * FTP_TRP_1_Admin.adoc 
    
5. Delete any .adoc SFRs files you do not want included in your test plan.
6. From the Menu, select the 'Actions' button.
7. Select **Combine Asciidoc, Convert to HTML, and Commit** workflow.
7. Select **Run workflow**. 

You can watch the workflow statusas it runs. Return to your repository's main page and download the 'combined-testplan.adoc' and/or 'testplan.html' documents.
