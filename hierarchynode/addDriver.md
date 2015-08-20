Note: If the driver is already assigned to another node in this hierarchy tree, it automatically moves to the new node.

Example Request:

https://api.gpsinsight.com/v2/hierarchy/adddriver?session_token=xxxx&tree=Division&node=Scottsdale&driver=Tom

Example Response:

    {
      head: { .... },
      data: "Driver added to node"
    }
