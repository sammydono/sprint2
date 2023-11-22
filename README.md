# sprint2

# Sunset Time Microservice

Welcome to the Sunset Time Microservice! This microservice provides information about the sunset time for a specific location.

### Requesting Sunset Time

To programmatically request sunset time data, make a `GET` request to the following endpoint:
GET /api/sunset?location={LOCATION}
curl -X GET "https://api.example.com/api/sunset?location=USER_INPUT"

### Return Sunset Time
{
  "sunset_time": "18:30:00"
}
