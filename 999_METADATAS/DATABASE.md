<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_ZZnMEKcTEe-MRc7bDGZ2kg" name="default" md:ref="resource.md#UUID_MD_RDBMS_ORACLE?fileId=UUID_MD_RDBMS_ORACLE$type=md$name=Oracle?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_ZZw9PqcTEe-MRc7bDGZ2kg" value="Oracle"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_xljLoKcTEe-MRc7bDGZ2kg" value="CSG2_ORA9"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_xlln4KcTEe-MRc7bDGZ2kg" value="oracle.jdbc.OracleDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_xlln4acTEe-MRc7bDGZ2kg" value="true"/>
  <attribute defType="com.stambia.rdbms.server.password" id="_xlmO8KcTEe-MRc7bDGZ2kg" value="CC91B92AF1C0218FFEDC45BF265B9571"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_xlmO8acTEe-MRc7bDGZ2kg" value="jdbc:oracle:thin:@//195.83.93.26:1521/SIAD_PDB2"/>
  <node defType="com.stambia.rdbms.schema" id="_Zeed8KcTEe-MRc7bDGZ2kg" name="CSG2_ORA9">
    <attribute defType="com.stambia.rdbms.schema.name" id="_Zgw88KcTEe-MRc7bDGZ2kg" value="CSG2_ORA9"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_ZgyyIKcTEe-MRc7bDGZ2kg" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_Zg2cgKcTEe-MRc7bDGZ2kg" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_Zg3DkKcTEe-MRc7bDGZ2kg" value="I_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.linkedServer" id="_rg1QIKcTEe-MRc7bDGZ2kg" value=""/>
    <node defType="com.stambia.rdbms.datastore" id="_xloEzKcTEe-MRc7bDGZ2kg" name="ARTICLE_EXP">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_xloEzacTEe-MRc7bDGZ2kg" value="ARTICLE_EXP"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_xloEzqcTEe-MRc7bDGZ2kg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_xloEz6cTEe-MRc7bDGZ2kg" name="COD_MRQ" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloE0KcTEe-MRc7bDGZ2kg" value="COD_MRQ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloE0acTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloE0qcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloE06cTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloE1KcTEe-MRc7bDGZ2kg" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloE1acTEe-MRc7bDGZ2kg" name="LIB_MRQ" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloE1qcTEe-MRc7bDGZ2kg" value="LIB_MRQ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloE16cTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloE2KcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloE2acTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloE2qcTEe-MRc7bDGZ2kg" value="26"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloE26cTEe-MRc7bDGZ2kg" name="COD_ART" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloE3KcTEe-MRc7bDGZ2kg" value="COD_ART"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloE3acTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloE3qcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloE36cTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloE4KcTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloE4acTEe-MRc7bDGZ2kg" name="LIB_PRD" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloE4qcTEe-MRc7bDGZ2kg" value="LIB_PRD"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloE46cTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloE5KcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloE5acTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloE5qcTEe-MRc7bDGZ2kg" value="40"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloE56cTEe-MRc7bDGZ2kg" name="LIB_COL" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloE6KcTEe-MRc7bDGZ2kg" value="LIB_COL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloE6acTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloE6qcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloE66cTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloE7KcTEe-MRc7bDGZ2kg" value="21"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloE7acTEe-MRc7bDGZ2kg" name="LIB_TAI" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloE7qcTEe-MRc7bDGZ2kg" value="LIB_TAI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloE76cTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloE8KcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloE8acTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloE8qcTEe-MRc7bDGZ2kg" value="9"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloE86cTEe-MRc7bDGZ2kg" name="FAM" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloE9KcTEe-MRc7bDGZ2kg" value="FAM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloE9acTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloE9qcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloE96cTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloE-KcTEe-MRc7bDGZ2kg" value="25"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloE-acTEe-MRc7bDGZ2kg" name="SS_FAM" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloE-qcTEe-MRc7bDGZ2kg" value="SS_FAM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloE-6cTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloE_KcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloE_acTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloE_qcTEe-MRc7bDGZ2kg" value="30"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloE_6cTEe-MRc7bDGZ2kg" name="PRX_VEN" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloFAKcTEe-MRc7bDGZ2kg" value="PRX_VEN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloFAacTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloFAqcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloFA6cTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloFBKcTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloFBacTEe-MRc7bDGZ2kg" name="LIB_GEN" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloFBqcTEe-MRc7bDGZ2kg" value="LIB_GEN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloFB6cTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloFCKcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloFCacTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloFCqcTEe-MRc7bDGZ2kg" value="6"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloFC6cTEe-MRc7bDGZ2kg" name="CIB_TRN_AGE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloFDKcTEe-MRc7bDGZ2kg" value="CIB_TRN_AGE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloFDacTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloFDqcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloFD6cTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloFEKcTEe-MRc7bDGZ2kg" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloFEacTEe-MRc7bDGZ2kg" name="COD_CAT" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloFEqcTEe-MRc7bDGZ2kg" value="COD_CAT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloFE6cTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloFFKcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloFFacTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloFFqcTEe-MRc7bDGZ2kg" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloFF6cTEe-MRc7bDGZ2kg" name="LIB_CAT" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloFGKcTEe-MRc7bDGZ2kg" value="LIB_CAT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloFGacTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloFGqcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloFG6cTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloFHKcTEe-MRc7bDGZ2kg" value="16"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_xlndGKcTEe-MRc7bDGZ2kg" name="TICKET_EXP">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_xlndGacTEe-MRc7bDGZ2kg" value="TICKET_EXP"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_xlndGqcTEe-MRc7bDGZ2kg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_xlndG6cTEe-MRc7bDGZ2kg" name="COD_ENS" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_xlndHKcTEe-MRc7bDGZ2kg" value="COD_ENS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xlndHacTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xlndHqcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xlndH6cTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xlndIKcTEe-MRc7bDGZ2kg" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xlndIacTEe-MRc7bDGZ2kg" name="LIB_ENS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_xlndIqcTEe-MRc7bDGZ2kg" value="LIB_ENS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xlndI6cTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xlndJKcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xlndJacTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xlndJqcTEe-MRc7bDGZ2kg" value="6"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xlndJ6cTEe-MRc7bDGZ2kg" name="LIB_MAG" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_xlndKKcTEe-MRc7bDGZ2kg" value="LIB_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xlndKacTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xlndKqcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xlndK6cTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xlndLKcTEe-MRc7bDGZ2kg" value="25"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xlndLacTEe-MRc7bDGZ2kg" name="COD_ART" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_xlndLqcTEe-MRc7bDGZ2kg" value="COD_ART"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xlndL6cTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xlndMKcTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xlndMacTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xlndMqcTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xlndM6cTEe-MRc7bDGZ2kg" name="DAT_HEU_TIC" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_xlndNKcTEe-MRc7bDGZ2kg" value="DAT_HEU_TIC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEIKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEIacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEIqcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEI6cTEe-MRc7bDGZ2kg" value="19"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEJKcTEe-MRc7bDGZ2kg" name="NUM_TIC" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEJacTEe-MRc7bDGZ2kg" value="NUM_TIC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEJqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEJ6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEKKcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEKacTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEKqcTEe-MRc7bDGZ2kg" name="NUM_TIC_LIG" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEK6cTEe-MRc7bDGZ2kg" value="NUM_TIC_LIG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloELKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloELacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloELqcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEL6cTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEMKcTEe-MRc7bDGZ2kg" name="COD_CAI" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEMacTEe-MRc7bDGZ2kg" value="COD_CAI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEMqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEM6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloENKcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloENacTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloENqcTEe-MRc7bDGZ2kg" name="COD_VEN" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEN6cTEe-MRc7bDGZ2kg" value="COD_VEN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEOKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEOacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEOqcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEO6cTEe-MRc7bDGZ2kg" value="6"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEPKcTEe-MRc7bDGZ2kg" name="QTE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEPacTEe-MRc7bDGZ2kg" value="QTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEPqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEP6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEQKcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEQacTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEQqcTEe-MRc7bDGZ2kg" name="MNT_BRU" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEQ6cTEe-MRc7bDGZ2kg" value="MNT_BRU"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloERKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloERacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloERqcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloER6cTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloESKcTEe-MRc7bDGZ2kg" name="MNT_TTC" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloESacTEe-MRc7bDGZ2kg" value="MNT_TTC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloESqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloES6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloETKcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloETacTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloETqcTEe-MRc7bDGZ2kg" name="COD_DEV" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloET6cTEe-MRc7bDGZ2kg" value="COD_DEV"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEUKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEUacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEUqcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEU6cTEe-MRc7bDGZ2kg" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEVKcTEe-MRc7bDGZ2kg" name="TX_TVA" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEVacTEe-MRc7bDGZ2kg" value="TX_TVA"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEVqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEV6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEWKcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEWacTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEWqcTEe-MRc7bDGZ2kg" name="REM_LIN" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEW6cTEe-MRc7bDGZ2kg" value="REM_LIN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEXKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEXacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEXqcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEX6cTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEYKcTEe-MRc7bDGZ2kg" name="REM_TIC" position="16">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEYacTEe-MRc7bDGZ2kg" value="REM_TIC"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEYqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEY6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEZKcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEZacTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEZqcTEe-MRc7bDGZ2kg" name="TX_DEV" position="17">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEZ6cTEe-MRc7bDGZ2kg" value="TX_DEV"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEaKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEaacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEaqcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEa6cTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEbKcTEe-MRc7bDGZ2kg" name="COD_PAY" position="18">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEbacTEe-MRc7bDGZ2kg" value="COD_PAY"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEbqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEb6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEcKcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEcacTEe-MRc7bDGZ2kg" value="2"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEcqcTEe-MRc7bDGZ2kg" name="LIB_PAY" position="19">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEc6cTEe-MRc7bDGZ2kg" value="LIB_PAY"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEdKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEdacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEdqcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEd6cTEe-MRc7bDGZ2kg" value="8"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEeKcTEe-MRc7bDGZ2kg" name="ADR1" position="20">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEeacTEe-MRc7bDGZ2kg" value="ADR1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEeqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEe6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEfKcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEfacTEe-MRc7bDGZ2kg" value="43"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEfqcTEe-MRc7bDGZ2kg" name="ADR2" position="21">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEf6cTEe-MRc7bDGZ2kg" value="ADR2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEgKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEgacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEgqcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEg6cTEe-MRc7bDGZ2kg" value="33"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEhKcTEe-MRc7bDGZ2kg" name="ADR3" position="22">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEhacTEe-MRc7bDGZ2kg" value="ADR3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEhqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEh6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEiKcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEiacTEe-MRc7bDGZ2kg" value="52"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEiqcTEe-MRc7bDGZ2kg" name="VIL_MAG" position="23">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEi6cTEe-MRc7bDGZ2kg" value="VIL_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEjKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEjacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEjqcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEj6cTEe-MRc7bDGZ2kg" value="22"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEkKcTEe-MRc7bDGZ2kg" name="COD_POS" position="24">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEkacTEe-MRc7bDGZ2kg" value="COD_POS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEkqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEk6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloElKcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloElacTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloElqcTEe-MRc7bDGZ2kg" name="DEP_MAG" position="25">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEl6cTEe-MRc7bDGZ2kg" value="DEP_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEmKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEmacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEmqcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEm6cTEe-MRc7bDGZ2kg" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEnKcTEe-MRc7bDGZ2kg" name="REG_MAG" position="26">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEnacTEe-MRc7bDGZ2kg" value="REG_MAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEnqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEn6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEoKcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEoacTEe-MRc7bDGZ2kg" value="26"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEoqcTEe-MRc7bDGZ2kg" name="TEL" position="27">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEo6cTEe-MRc7bDGZ2kg" value="TEL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEpKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEpacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEpqcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEp6cTEe-MRc7bDGZ2kg" value="17"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEqKcTEe-MRc7bDGZ2kg" name="EMAIL" position="28">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEqacTEe-MRc7bDGZ2kg" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEqqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEq6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloErKcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEracTEe-MRc7bDGZ2kg" value="31"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloErqcTEe-MRc7bDGZ2kg" name="LNG" position="29">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEr6cTEe-MRc7bDGZ2kg" value="LNG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEsKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEsacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEsqcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEs6cTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEtKcTEe-MRc7bDGZ2kg" name="LAT" position="30">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEtacTEe-MRc7bDGZ2kg" value="LAT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEtqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEt6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEuKcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEuacTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEuqcTEe-MRc7bDGZ2kg" name="DAT_OUV" position="31">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEu6cTEe-MRc7bDGZ2kg" value="DAT_OUV"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEvKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEvacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEvqcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEv6cTEe-MRc7bDGZ2kg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloEwKcTEe-MRc7bDGZ2kg" name="DAT_FRM" position="32">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEwacTEe-MRc7bDGZ2kg" value="DAT_FRM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEwqcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEw6cTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloExKcTEe-MRc7bDGZ2kg" value="FLOAT"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloExacTEe-MRc7bDGZ2kg" value="126"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_xloExqcTEe-MRc7bDGZ2kg" name="SCHEDULE" position="33">
        <attribute defType="com.stambia.rdbms.column.name" id="_xloEx6cTEe-MRc7bDGZ2kg" value="SCHEDULE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_xloEyKcTEe-MRc7bDGZ2kg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_xloEyacTEe-MRc7bDGZ2kg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_xloEyqcTEe-MRc7bDGZ2kg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_xloEy6cTEe-MRc7bDGZ2kg" value="174"/>
      </node>
    </node>
  </node>
</md:node>