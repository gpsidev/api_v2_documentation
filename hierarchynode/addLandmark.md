Note: If the landmark is already assigned to another node in this hierarchy tree, it automatically moves to the new node.

Example Request:

https://api.gpsinsight.com/v2/hierarchy/addlandmark?session_token=xxxx&tree=Division&node=Scottsdale&landmark=Scottsdale%20Municipal%20Airport

Example Response:

    {
      head: { .... },
      data: "Landmark added to node"
    }
