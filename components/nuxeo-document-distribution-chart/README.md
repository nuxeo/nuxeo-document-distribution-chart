[![Build Status](https://qa.nuxeo.org/jenkins/buildStatus/icon?job=nuxeo-document-distribution-chart-master)](https://qa.nuxeo.org/jenkins/job/nuxeo-document-distribution-chart-master/)

# About nuxeo-document-distribution-chart

**Nuxeo Document Distribution Chart** is a Polymer element for displaying Document distribution of a Nuxeo repository within a sunurst chart built upon d3js.

## Limitations

The *size* mode does not properly take into account the size of the Versions of Documents.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Quickstart

We recommend that you use [Polyserve](https://github.com/PolymerLabs/polyserve) which you can install via:

    npm install -g polyserve

And you can run it via:

    polyserve -p 3000

Once running, you can checkout the docs and demo at `http://localhost:3000/components/nuxeo-document-distribution-chart/`.

## Testing

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/nuxeo-document-distribution-chart/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.

## Documentation

- [Online](http://nuxeo.github.io/nuxeo-document-distribution-chart/components/nuxeo-document-distribution-chart/) reference and demos.

## Report & Contribute

We are glad to welcome new developers on this initiative, and even simple usage feedback is great.
- Ask your questions on [Nuxeo Answers](http://answers.nuxeo.com)
- Report issues on our [JIRA](https://jira.nuxeo.com/browse/ELEMENTS/component/15314/)
- Contribute: Send pull requests!

##About Nuxeo
Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris. More information is available at [www.nuxeo.com](http://www.nuxeo.com).
