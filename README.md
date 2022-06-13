# Tektonを使ったk8sアプリケーションのソース一式
本リソースとは別にingressに割り当てるFQDNが必要です。GCPならCloud Domain、AWSならRoute53を使って、グローバルIPからFQDNを作成するようにしてください。
※ソースはGKEとEKSを用いて実行確認をしたものです。


## Tektonとは
[Tekton](https://tekton.dev/) はk8sでCI/CDを実現するオープンソースフレームワークです。
k8sを用いたCI/CDツールはいくつかありますが、一部にTektonが使われています。

