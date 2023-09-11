# DMM-WEBCAMP-AWS-termexplanation
# AWS用語説明
## AWS用語
### リージョン
#### AWSがサービスを提供しているエリア（国・地域）のこと。地理的に離れた位置に独立したデータセンターを設置し、それぞれを接続する仕組み。現在、世界各地に20以上のリージョンがある。

### AZ(アベイラビリティーゾーン)
#### データセンターのことで、実際にサービスが稼働する場所のこと。東京リージョンには4つのAZが存在。


## SDK・CLI
### AWS SDK(Software Development Kit)
#### AWSが提供する公式ライブラリの1つ。プログラミング言語でAWSのサービスを呼び出すことが出来る。

### AWS CLI(Command Line Interface)
#### LinuxやWindowsのコマンドラインでAWSのサービスを操作するのに使用。


## AWS 利用サービス説明
### EC2（Amazon Elastic Compute Cloud）
### AWSが提供するクラウドコンピューティングサービス。インスタンスという単位で仮想マシンを管理している。

### パブリックIPv4アドレス（グローバルIPアドレス）
#### インターネットからアクセス可能なIPアドレス。このIPアドレスはインターネット上で必ず一意に割り振られる。

### プライベートIPv4アドレス
#### インターネットからアクセスができないIPアドレス。VPCインスタンス間の通信で利用可能。

### EIP(Elastec IP)
#### AWSで固定IPアドレスを利用するためのサービス。

### AMI(Amazonマシンイメージ)
#### EC2インスタンスの構成を取得し、テンプレートを作成するサービス。EC2インスタンスの全内容をバックアップすることができる。

### EBS(Elastic Block Store)
#### ネットワークを介してEC2インスタンスにアタッチされるボリューム。

### インスタンスストア	
#### EC2インスタンスに直接アタッチされるボリューム。インスタンスを停止・終了すると内容が消える。

### Amazon EFS
#### AWSが提供するNFS(Network File System)を使用するファイルストレージ。EC2インスタンスのボリュームとして利用することが可能。

### ロードバランサー
#### ALB（Application Load Balancer）・NLB（Network Load Balancer）・Classic Load Balancer(旧来のロードバランサーでELBと呼ばれていました)の3種類をサポートする。

### ALB(Application Load Balancer)
#### アプリケーションへのトラフィックを複数のターゲットに分散するサービス。


### AWS Lambda
### AWSが提供するサーバーの起動や管理なしで、コード（Lambda 関数）を自動実行できるサービス。Node.js/Python/Java/Go/Ruby/.NET Coreといったプログラミング言語に対応している。

### レイヤー(Lambda レイヤー)
#### ライブラリを複数のLambda 関数で共有することが可能。
