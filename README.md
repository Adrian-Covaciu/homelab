# 🏠 Homelab

## Introduction

This repo contains my implementation of homelab. It's purpose is to learn about FluxCD, Kubernetes and have a personal homepage for my CV.

## Cluster Provisioning

I use Raspberry Pi OS to setup my lightweight K3s cluster.

## :computer: Hardware & Networking

My servers are two Raspberry Pi's, one large and one small. These are what was available for me at the time, yet enough to play around and host my homepage.

Raspberry Pi 5 8GB
Raspberry Pi 4 1GB

I use a Unifi Cloud Gateway Ultra configured with 2 VLAN's, one for internet exposed servers and one for WI-FI devices. I also make use of it's features for IPD/IDS and blocking certain countries.

## Installed Apps & Infrastructure tools

### Application

For the moment this is the only application I require.

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://github.com/gethomepage/homepage/blob/dev/images/banner_light%402x.png"></td>
        <td><a href="https://gethomepage.dev/">Homepage</a></td>
        <td>No code, easy to use and configure homepage</td>
    </tr>
</table>

### Infrastructure

Infrastracture tools I used to achieve my goal of hosting.

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/svg/cert-manager.svg"></td>
        <td><a href="https://cert-manager.io/">Cert Manager</a></td>
        <td>X.509 certificate management for Kubernetes.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/flux-cd.svg"></td>
        <td><a href="https://fluxcd.io/">Flux CD</a></td>
        <td>My GitOps solution of choice. Better than Argo.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/svg/grafana.svg"></td>
        <td><a href="https://grafana.com/">Grafana</a></td>
        <td>The open observability platform.</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/svg/prometheus.svg"></td>
        <td><a href="https://prometheus.io/">Prometheus</a></td>
        <td>An open-source monitoring system with a dimensional data model, flexible query language, efficient time series database and modern alerting approach.</td>
    </tr>
<table>

## :runner: Next steps

Automate certificate renewal with Github Actions and Unifi API (when it's mature enough, at the moment in beta).
Secure my cluster further with Network Policies.


## Credits

To [Misha](https://github.com/mischavandenburg/homelab) as this is where I got the idea and inspiration.