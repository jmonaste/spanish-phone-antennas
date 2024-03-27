Description:

This project collects information about mobile phone antennas in Spain. The information is obtained from the Service for information on radioelectric stations and exposure levels of the Ministry of Industry, Trade and Tourism.

Objective:

The objective of this project is to create a complete and up-to-date database of mobile phone antennas in Spain, with information about their location, technical characteristics and exposure levels to radioelectric emissions.

Methodology:

The extreme coordinates of the Iberian Peninsula are determined.
The peninsula is traversed from west to east and from north to south, obtaining the information of the antennas through the API of the web service of the Ministry.
The information is stored in a database with the following tables:
estaciones_telefonia_movil: general information of the stations
localizaciones_antenas: information about the location of the antennas
caracteristicas_tecnicas_antenas: technical information of the antennas
niveles_medidos_entorno_antenas: exposure levels measured in the environment of the antennas
detalle_ejecucion: information about the data extraction process
Technologies:

Python
MySQL
API of the Ministry of Industry, Trade and Tourism
Database:

The database is in the database.sql file.

Execution:

To run the project, follow these steps:

Install the dependencies:
pip install requests beautifulsoup4
Create the database and run the main.py file:
python main.py
Contributions:

Contributions to the project are welcome. You can collaborate in the following ways:

Reporting bugs or problems.
Suggesting improvements or new features.
Contributing code to the project.
License:

This project is licensed under the MIT license.

Contact:

For any questions or queries, contact the author of the project through the email address [author's email address].

Additional Resources:

Service for information on radioelectric stations and exposure levels: https://geoportal.minetur.gob.es/VCTEL/vcne.do
API of the Ministry of Industry, Trade and Tourism: https://www.youtube.com/watch?v=lOeQUwdAjE0 information technologies/topics/radio spectrum management/api/
Next Steps:

Implement an automatic database update process.
Develop a web interface to query the information in the database.
Analyze the data to obtain information about the coverage of mobile networks and the exposure levels to radioelectric emissions in Spain.
