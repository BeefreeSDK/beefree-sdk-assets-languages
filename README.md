## Custom Languages

In this repo, you will find example language translation templates you can use with  [BEE Plugin](https://beefree.io/bee-plugin/), an embeddable drag and drop content editor. For an overview of this feature, please refer to our  [dedicated page](https://docs.beefree.io/custom-languages/)  in our documentation website.

### Usage
1. Use the default translations provided with BEE Plugin with the `language` configuration property (client-side), e.g. `language: 'es-ES'` for Spanish.

2. Use the `translationsUrl` property (in the client-side configuration) to provide the URL of a self-hosted version of the translations of BEE Plugin. Consider these JSON files as a starting point and customize them with your own labels. This solution requires a HTTPs server to host the file(s) with the correct CORS policies.

3. Use the content (or part of the content) direcly in the `translations` property in the client-side configuration object of BEE Plugin to override specific terms.

Please refer to the [offical documentation](https://docs.beefree.io/custom-languages/) for updated details and configuration examples.
