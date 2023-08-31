## Custom Languages

In this repo, you will find example language translation templates you can use with  [Beefree SDK](https://beefree.io/bee-plugin/), an embeddable drag-and-drop content editor. For an overview of this feature, please refer to our  [dedicated page](https://docs.beefree.io/custom-languages/)  on our documentation website.

### Usage
1. Use the default translations provided with Beefree SDK with the `language` configuration property (client-side), e.g., `language: 'es-ES'` for Spanish.

2. Use the `translationsUrl` property (in the client-side configuration) to provide the URL of a self-hosted version of the translations of Beefree SDK. Consider these JSON files as a starting point and customize them with your own labels. This solution requires an HTTPs server to host the file(s) with the correct CORS policies.

3. Use the content (or part of the content) directly in the `translations` property in the client-side configuration object of Beefree SDK to override specific terms.

Please refer to the [official documentation](https://docs.beefree.io/custom-languages/) for updated details and configuration examples.
