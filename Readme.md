#Make sure Python latest version is intalled
<ul>
   <li>Create .env file with contents
        DB_USER=yourpostgresusename
        DB_PASSWORD=yourpostgrespassword
        DB_NAME=biologicalsamples
    </li>
  
  <li>Run the command <strong>python -m venv .venv</strong></li>
  <li>Activate the virtual env by  running command(forwindows) <strong> .venv/Scripts/Activate.ps1</strong> </li>
  <li>Run the command <strong>pip install -r requirements.txt</strong> to install all libraries </li>
  <li>Installed Postgres</li>
  <li>Create a database with a name <strong>biologicalsamples</strong></li>
  <li>Create a table for vcf_metadata use the sql query provided (create_table_vcfmetadata.sql) and run it on postgres </li>

  <li>Run the command <strong>uvicorn app:app --reload</strong> to run the app</li>
</ul>
