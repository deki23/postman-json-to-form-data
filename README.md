# Postman JSON to form-data

This tool aims to provide users with a quick way to move from JSON to form data in Postman.

[Preview Page](https://deki23.github.io/postman-json-to-form-data)

## How to use

- Copy your raw JSON from the Postman request

![App Screenshot](https://github.com/deki23/postman-json-to-form-data/assets/48088941/5e2ddaae-9058-40b1-bdfd-227d9b913049)

- Use [preview link](https://deki23.github.io/postman-json-to-form-data) and paste your raw JSON into the textarea and click "Convert"

- Go to the Bulk Edit option for form-data

![Bulk Edit](https://github.com/deki23/postman-json-to-form-data/assets/48088941/a7519267-83f6-4deb-8ce8-44a00b3ec8ed)

- Paste the generated raw form data to the Bulk Edit area in Postman

![Paste raw form-data](https://github.com/deki23/postman-json-to-form-data/assets/48088941/ec5c2df4-e71b-414f-9211-7d851629da43)

- Optionally, go back to "Key-Value Edit" if you need to add files to the request or check the request before sending

![Key Value Edit](https://github.com/deki23/postman-json-to-form-data/assets/48088941/f7685bc9-eddd-4d5f-856d-77b7964d18d7)

## Roadmap

- Design improvements
- Error reporting
- Write tests
- Add option to do it vice-versa, form-data to JSON

## Limitations

Since this uses recursion when it finds nested objects, it may not work for massive data, e.g., more than 1000 nested entries.
## Support

If you find any bugs, feel free to submit a GitHub issue.

## License

This project is [MIT licensed.](https://github.com/deki23/postman-json-to-form-data/blob/main/LICENSE)