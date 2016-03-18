## Doblst
Simple python script for managing digitalocean's Beta Block Storage

**Remember to add your API key to the top of the script**

Requests is requierd, install requests using pip:
```
pip install requests
```

## Usage
 * doblst list[l] - lists all your drives
 * doblst new[n]  - Create new drive
 * doblst remove[r] [drive ID] - Remove drive
 * doblst attach[a] [drive ID] [droplet ID] - attach drive to droplet
 * doblst detach[d] [drive ID] - detach drive from droplet
