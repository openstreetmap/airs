# Aerial Imagery Request System (AIRS)

AIRS is an issue tracker designed to streamline the requesting of aerial imagery for OpenStreetMap contributors.

It verifies requests against existing imagery, ensuring there are no overlaps with current data.

## Features

- **Polygon Submission**: Users submit requests using GeoJSON to specify the area of interest - which can be as simple as a box or as detailed as a country's border.
- **Imagery Quality Criteria**: Users indicate the desired resolution and time box for imagery requests.
- **Automated Validation**: Automated checks for overlap with existing aerial imagery.

## Getting Started

### Prerequisites

- GitHub Account
- Basic understanding of GeoJSON format

### Submitting an Imagery Request

1. **Navigate to the Issues tab** of the AIRS GitHub repository.
2. **Click on 'New Issue'** and choose the Aerial Imagery Request template.
3. **Fill out the form**:
   - **Title**: Provide a concise title for your imagery request.
   - **Location Polygon (GeoJSON)**: Use [geojson.io](http://geojson.io/) to draw your area or download pre-defined poly files from [Geofabrik](http://downloads.geofabrik.de) and upload them there. Save the geojson file and attach it to your issue.
   - **Resolution**: Select the desired resolution (High, Medium, Low).
   - **Time Box**: Specify the timeframe for which the imagery is relevant.
4. **Submit the issue**. Your request will be automatically validated, and be available for imagery providers to answer.

### Receiving Feedback

- Once your request is automatically validated, you will receive a comment detailing the results.
- If an imagery provider is interested in providing imagery, they will comment on your issue.

## Contributing imagery

If you are an imagery provider, contributions to AIRS are welcome! Here’s how you can help:

- **Locking an issue**: To avoid double work, comment on an issue if you are working on it.
- **Adding imagery to indexes**: Add your imagery to the indexes at [ELI](https://github.com/osmlab/editor-layer-index/) and [JOSM](https://josm.openstreetmap.de/wiki/Maps).
- **Comment on issue**: If your new imagery covers some or all of a request, comment on the issue.
