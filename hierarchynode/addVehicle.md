Note: If the vehicle is already assigned to another node in this hierarchy tree, it automatically moves to the new node.

Example Request:

https://api.gpsinsight.com/v2/hierarchynode/addvehicle?session_token=xxxx&tree=Division&node=Scottsdale&vehicle=Truck150

Example Response:

    {
      head: { .... },
      data: "Vehicle added to node"
    }
