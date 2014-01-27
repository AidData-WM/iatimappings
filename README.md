#IATI Field Mappings

This repository contains mappings made between values occuring in the IATI repository and official values from the IATI code list. These were produced during the beta IATI data import for <a href="http://www.aiddata.org">aiddata.org</a>.

##mapped_iati_orgs.csv

Contains mappings between values for organizations in the registry (<reporting-org>, <participating-org>, <provider-org>, <receiver-org>) and values in the IATI code list. Columns:

-"xml_@ref" : the value for the organization's @ref attribute occuring in the XML element in the IATI registry
-"xml_text()" : the value for the organization's XML element's text occuring in the IATI registry
-"aiddata_id" : the equivalent ID code for the organization in the AidData database
-"iati_org_code" : the equivalent ID code for the organization in the IATI Code list
-"iati_org_name" : the correct organization name according to the IATI Code list

Values are encapsulated with double quotes ("). Columns are delimited with commas (,). Double quotes within values are escaped with back-slashes (\"). Non-escape-character back-slashes are also escaped (\\). Encoding right now is a problem and will be corrected soon (see open issue).
