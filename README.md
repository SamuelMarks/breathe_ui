# Elastcisearch UI for [BioMedBERT2 project][BERT2]

## About

This is a UI for [BigMedBioBERT2 project][BERT2] dataset Elasticsearch index.

## Deployment

This project is meant to be deployed to Netlify.

A `netlify.toml` file is included with all of the configuration you'll need to deploy it to Netlify.

You'll additionally need to configure `ELASTICSEARCH_HOST` as an environment variable.

## Contributing

### Setup

Just clone the project and run the following in this directory:

```
npm install
```

### Run

Run the following command, filling in the variables below with your own Elasticsearch credentials and host.

```
ELASTICSEARCH_HOST=https://{user}:{password}@{elasticsearch_url} npm start
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

[BERT2]: https://github.com/ivankozlovcodes/BioMedBERT2 "BigBioMedBERT2"