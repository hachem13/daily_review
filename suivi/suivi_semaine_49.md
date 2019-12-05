# suivi semaine 49 

  ## 05/12/2019 

    * veille

  ## 04/12/2019 
      
    * clé SSh github (A) 
    * veille sur read the docs 
    
  ## 03/12/2019 

    
    * exercice sql  
    

  ## 02/12/2019 

    * modele relationnel des données 

    * exercice d’auto_entrepreneur 
    
 corrigée:

    * client ( CL_ID, CL_nom, CL_prénom, CL_tel)

    * matériel (MA_ID, MA_ref, MA_type, #CL_ID)
    
    * type d’entretien ( TP_ID, TP_type, TP_prix_horaire)

    * intervention (IN_ID, #MA_ID, #TP_ID, IN_data, IN_durée, IN_prix_total)

    * pièce ( PI_ref, PI_prix)

    * pièce utilisé (#IN_ID, #PI_ref)
 
 
exercice sportif

 corrigé

    * sportif (SP_ID, SP_nom, SP_prénom, SP_adresse, SP_ville, SP_code_postale, SP_téléphone, SP_email, SP_fax, SP_certificat, SP_licence, SP_nom_club)

    * inscription (INS_ID, INS_num_dossard, INS_date, #SP_ID, #CPT_ID)

    * competition (CPT_ID, CPT_nom, CPT_ville, CPT_date, CPT_nbre_épreuve)

    * épreuve (EP_ID, EP_type, EP_ordre, EP_distance, EP_condition)

    * composition compétition (#CPT_ID, #EP_ID)
