# Go-Blockchain
This is a Golang based implementation of a basic blockchain.

## Testing and Development
- Clone the project
- Choose the running port in the `.env` file in root. Currently it runs on `localhost:8080`
- Run `go run main.go`
- Open a web browser and visit `http://localhost:8080/`. You will see the genesis block here.
- To write new blocks, send a POST request (I like to use Postman) to `http://localhost:8080/` with a JSON payload with `BPM` as the key and an integer as the value. For example:
```
{"BPM":50}
```
- Send as many requests as you like and refresh your browser to see your blocks grow! Use your actual heart rate (Beats Per Minute) to track it over time.

## Screenshot

![](https://user-images.githubusercontent.com/29003047/115970284-05a35b00-a55f-11eb-980c-1f719c9d3e2b.png)