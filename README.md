# hcloud
Simple Dockerimage for hcloud

Usage:

Basic hcloud command:
 * docker run -it --rm askoproducts/hcloud hcloud


List all your servers:
 * docker run -it -e HCLOUD_TOKEN=YOURHETZNERCLOUDAPITOKEN --rm askoproducts/hcloud hcloud server list


Environment variables:
 * HCLOUD_TOKEN (your api token)
