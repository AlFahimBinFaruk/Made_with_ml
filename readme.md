## Core Features

- Predict the correct tag for a given content.
- User feedback process for incorrectly classified content.
- Workflows to categorize ML content that our model is incorrect or unsure about.

## Integrations

- ML content from reliable sources will be sent to our service for classification.

## Constraints

- **Maintain low latency (<100ms)** when classifying incoming content. _(Latency)_
- **Only recommend tags from our list of approved tags.** _(Security)_
- **Avoid duplicate content** from being added to the platform. _(UI/UX)_

## Tasks

- [x] Fetch the data.
- [x] Format the Data.
- [x] Tokenize the data.
- [x] Data Distribution with Ray.
