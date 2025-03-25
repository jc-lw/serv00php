# 哪吒V1 部署到 serv00 
## serv00_nezha_dashboard.sh 为哪吒V1面板适应serv00部署
bash <(curl -Ls https://raw.githubusercontent.com/jc-lw/serv00php/refs/heads/main/serv00_nezha_dashboard.sh)
## serv00_public.sh 为哪吒监控agent适应serv00部署
bash <(curl -Ls https://raw.githubusercontent.com/jc-lw/serv00php/refs/heads/main/serv00_public.sh)

## bh.sh 为安装哪吒监控agent创建并运行 restart.sh 和 start.sh 
bash <(curl -Ls https://raw.githubusercontent.com/jc-lw/serv00php/refs/heads/main/bh.sh)

