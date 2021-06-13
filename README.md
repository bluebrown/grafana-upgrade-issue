# Grafana upgrade issue

1. use 7.5.7 in the compose file
2. compose up
3. navigate to <http://localhost:3000/plugins/grafana-clock-panel/> (all good)
4. compose down
5. change version to `latest`
6. compose up
7. navigate to <http://localhost:3000/plugins/grafana-clock-panel/> // (404)

I noticed this warning appearing  <http://localhost:3000/plugins/> in the latest version but not 7.5.7

![image](https://user-images.githubusercontent.com/39703898/121804262-61c05c80-cc3d-11eb-813e-d94ae4b79d2d.png)
