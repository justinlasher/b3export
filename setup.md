# run this the setup the access to the api....

curl -H "Authorization: Bearer $ACCESS_TOKEN" \
  -H 'Content-Type: application/json' \
  -H 'User-Agent: CustomExport (justin.lasher@gmail.com)' \
  -d '{ "name": "Custom export tool!" }' \
  https://3.basecampapi.com/3272645/projects.json
