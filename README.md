`taaabs-csv-schema` is graphical element in which the user can edit the properties of a trace csv file.

### Example :

A `taaabs-csv-schema` not preset

   <taaabs-csv-schema></taaabs-csv-schema>

A `taaabs-csv-schema` with all its attributes preset

    <taaabs-csv-schema  id="csvSchema"
                 csv-schemas="{{csvSchemas}}"
                 base="{{base}}"
                 files="{{files}}"
                 csv-schema="{{csvSchema}}">
    </taaabs-csv-schema>

@element taaabs-csv-schema
