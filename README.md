# Public Transport Ontology Project

**Authors :** *Ihab Bendidi*, *Clément Siegrist* 

Flask app development by Ihab Bendidi, Protégé-Ontology development by Clément Siegrist.
For more details on the content of our ontology and our work consults our report [here](https://github.com/clementsiegrist/transport_ontology_API/blob/main/OWS_SIegristBendidi.pdf) and/or or oral presentation [here](https://github.com/clementsiegrist/transport_ontology_API/blob/main/Ontologie_transport_Prote%CC%81ge%CC%81-compressed.pdf)

### Installation :

On the root folder of the project, run on terminal :

```
pip3 install -r requirement.txt
```

### Usage :

To launch the app, on the root folder of the project, run on terminal :

```
python3 app.py
```

A front end of the web app is accessible at `http://127.0.0.1:5000`

### APIs to use :

```
curl -X GET 'http://127.0.0.1:5000/api/moyen_transports'
```


```
curl -X GET 'http://127.0.0.1:5000/api/individu_transports?individu=Alexis'
```


```
curl -X GET 'http://127.0.0.1:5000/api/statistics?moyen=Uber'
```


```
curl -X GET 'http://127.0.0.1:5000/api/pollution?moyen=bus'
```


```
curl -X GET 'http://127.0.0.1:5000/api/get_details?location=eiffel+tower'
```
