Note: Our integration of Garmin's FMI protocol allows for three types of "Canned" items to be stored on compatible devices that support the A604 protocol. For the purpose of organization in our API, we consider Message, Response, and Driver Status to be three types of Canned Message Groups, and a Garmin device can be the member only one of each type of Canned Message Group. As example, we have two Groups of type Message: Group A and Group B. While the same Canned Message can be a member of each group, a Garmin device can only be a member of either Group A or Group B, and cannot be a member of both Group A and Group B concurrently.

Example Request: https://api.gpsinsight.com/v2/dispatch/createcannedmessage?session_token=xxxx&message=Lunch%20Break&type=Status

Example Response:

    {
      head: { .... },
      data: [
        {
          message_id: "1001863",
          result: "Created"
        }
      ]
    }
