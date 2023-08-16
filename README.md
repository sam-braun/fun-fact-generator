# Fun Fact Generator

The Fun Fact Generator is a simple web application that allows users to fetch and display random fun facts. With just a click of a button, users can learn interesting facts on a variety of topics.

## How It Works

1. When the page loads, you will see a title ("Fun Fact Generator") and a button (labeled "Get Fun Fact").
2. Clicking the "Get Fun Fact" button triggers an AJAX request to an external API that provides random fun facts.
3. The API response is processed, and the displayed fun fact text alternates between different colors for each fact.
4. The fact container will display the fetched fun fact along with the alternating text color.

## Technologies Used

- HTML: For structuring the web page.
- CSS: For styling the page elements and applying formatting.
- JavaScript (jQuery): For handling button click events, making AJAX requests, and updating the page content.
- [API-Ninjas API](https://api.api-ninjas.com/v1/facts): The external API used to fetch random fun facts.

## How to Use

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Click the "Get Fun Fact" button to fetch and display a random fun fact.

## Credits

The random fun facts are provided by the [API-Ninjas API](https://api.api-ninjas.com/v1/facts). Special thanks to API-Ninjas for making this data available.

## License

This project is licensed under the [MIT License](LICENSE).
