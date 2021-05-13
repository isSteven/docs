# `isSteven` API
## `isSteven` in your photo?
The isSteven API accepts a base 64 encoded JPG/JPEG or PNG.

### Input 
```bash
curl --header "Content-Type: application/json" \
  --request POST \
  --data '{"image":"Base64 encoded PNG/JPEG/JPG"}' \
  https://api.issteven.xyz/
```

### Output
```json
{
  "conclusion": "This image is 78.09 percent steven and 21.91 percent !steven.", 
  "stevenness_percentage": "78.09", 
  "isSteven": true
}
```

## What `isSteven`?
What `isSteven` outputs an image of Steven

### Input
```bash
curl https://api.issteven.xyz/what
```

### Output
```json
{
  "message": "thanks for using this api!",
  "steven": imageURL,
  "random": "your lucky number is 1"
}
```

# Contributors
- [Jia Chen](https://github.com/jiachenyee)
- [Faisal](https://github.com/faisalsgithub)
- [Lik Hern](https://github.com/YeohLikHern)
- [James Chen](https://github.com/unknownguy2002)
- [Rui Yang](https://github.com/thinkerpal)
