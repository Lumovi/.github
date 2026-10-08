<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lumovi/.github/main/profile/images/banner-dark.png" />
  <img src="https://raw.githubusercontent.com/Lumovi/.github/main/profile/images/banner-light.png" alt="Lumovi. Your clusters, at a glance. A calm, fast Kubernetes dashboard, on your desktop or in your cluster." />
</picture>

<p align="center">
  <a href="https://lumovi.dev"><b>lumovi.dev</b></a>
  &nbsp;·&nbsp;
  <a href="https://docs.lumovi.dev">Documentation</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Lumovi/Lumovi/releases/latest">Download</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Lumovi/Lumovi">Source</a>
</p>

Lumovi shows what's healthy in your Kubernetes clusters, what's struggling and where to look
first, and lets you fix things safely when they need it. It's one open-source app you run two
ways: **on your desktop**, for every cluster in your kubeconfig, or **in your cluster**, for your
whole team to open in a browser.

<a href="https://github.com/Lumovi/Lumovi">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/overview-dark.webp" />
    <img src="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/overview-light.webp" alt="Lumovi's overview of a cluster: nodes, pods and workloads, CPU and memory with their last hour, and what needs attention." />
  </picture>
</a>

## Two ways to run it

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>On your desktop</h3>
      <p>For macOS, Windows and Linux. Every cluster in your kubeconfig, with its own credentials,
      and port forwards and Helm charts from your computer. It updates itself.</p>
      <p><a href="https://github.com/Lumovi/Lumovi/releases/latest"><b>Download Lumovi →</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>In your cluster</h3>
      <p>A Helm chart serves the same app to your team. People sign in with a token, single
      sign-on or your proxy, see what their own RBAC allows, and share links to any page.</p>
      <p><a href="https://docs.lumovi.dev/server/install"><b>Install it with Helm →</b></a></p>
    </td>
  </tr>
</table>

## What it shows you

<table>
  <tr>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/map-dark-1x.webp" />
        <img src="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/map-light-1x.webp" alt="A deployment's map, from its gateway to the nodes its pods run on." />
      </picture>
      <h3>How everything connects</h3>
      <p>Every object's map: what leads to it, from gateways to services, and what it uses and
      runs on, down to the node.</p>
    </td>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/logs-dark-1x.webp" />
        <img src="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/logs-light-1x.webp" alt="The logs of every pod of a deployment, merged as they happened." />
      </picture>
      <h3>Logs as they happen</h3>
      <p>Every pod of a workload in one stream, merged by time, with search, levels and ANSI
      colors.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/right-sizing-dark-1x.webp" />
        <img src="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/right-sizing-light-1x.webp" alt="Right-sizing: what each workload should request, from a week of its usage." />
      </picture>
      <h3>Requests that fit</h3>
      <p>What each workload should request, from a week of its usage in Prometheus or
      VictoriaMetrics, with the reasons, applied after a dry run.</p>
    </td>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/add-on-dark-1x.webp" />
        <img src="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/add-on-light-1x.webp" alt="Flux's add-on: everything Flux runs in one list, what's failing first." />
      </picture>
      <h3>Every tool you run</h3>
      <p>A page for each: Argo CD, Flux, cert-manager, Karpenter and 28 more, with what's failing
      first.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/helm-dark-1x.webp" />
        <img src="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/helm-light-1x.webp" alt="A Helm release's history, ready to roll back." />
      </picture>
      <h3>Helm releases</h3>
      <p>Their history, values and objects. Upgrade, roll back or install, once a dry run has
      shown what changes.</p>
    </td>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/yaml-dark-1x.webp" />
        <img src="https://raw.githubusercontent.com/Lumovi/Lumovi/main/docs/screenshots/yaml-light-1x.webp" alt="A change to a ConfigMap's YAML, checked by the cluster and shown before it's saved." />
      </picture>
      <h3>Changes, safely</h3>
      <p>Edits checked by the cluster and shown as a diff before they're saved, permissions
      checked first, the kubectl command for every change, and undo.</p>
    </td>
  </tr>
</table>

## Get involved

- **Try it**: [download the desktop app](https://github.com/Lumovi/Lumovi/releases/latest), or
  run it from source with `npm run dev:mock`, against demo clusters.
- **Missing a tool?** Teaching Lumovi a new one is a YAML file, with no code:
  [adding a tool](https://github.com/Lumovi/Lumovi/blob/main/CONTRIBUTING.md#adding-a-tool).
- **Found a bug, or have an idea?** [Open an issue](https://github.com/Lumovi/Lumovi/issues/new/choose).
- **Like it?** Star [Lumovi](https://github.com/Lumovi/Lumovi), or
  [sponsor its development](https://github.com/sponsors/kotapeter).

<sub>Lumovi is open source under the Apache 2.0 license. Kubernetes is a registered trademark of
the Linux Foundation.</sub>
