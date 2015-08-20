Note: If the user is already assigned to another node in this hierarchy tree, it automatically moves to the new node.

Example Request:

https://api.gpsinsight.com/v2/hierarchynode/adduser?session_token=xxxx&tree=Division&node=Scottsdale&username=tgypsy

Example Response:

    {
      head: { .... },
      data: "User added to node"
    }
