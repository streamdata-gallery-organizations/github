{
  "info": {
    "name": "Github Get Repos Owner Repo Stats Punch Card",
    "_postman_id": "0b69fab0-7994-41fb-bb5c-3aedd74ddb18",
    "description": "Get the number of commits per hour in each day.\nEach array contains the day number, hour number, and number of commits\n0-6 Sunday - Saturday\n0-23 Hour of day\nNumber of commits\n\nFor example, [2, 14, 25] indicates that there were 25 total commits, during\nthe 2.00pm hour on Tuesdays. All times are based on the time zone of\nindividual commits.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repos",
      "item": [
        {
          "id": "71792804-ac0f-4850-80a2-97b9390b13e6",
          "name": "get-the-number-of-commits-per-hour-in-each-dayeach-array-contains-the-day-number-hour-number-and-num",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.github.com",
              "path": [
                "repos/:owner/:repo/stats/punch_card"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "owner",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "repo",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "Is used to set specified media type",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the number of commits per hour in each day"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54a0e081-580c-4065-8604-460f263d4740"
            }
          ]
        }
      ]
    }
  ]
}