# Zenth Proxy Server

**Zenth Proxy Server** is a robust, open-source proxy solution developed by Sky Genesis Enterprise for the Zenth Cloud ecosystem. It enables secure, scalable, and high-performance proxying for HTTP, HTTPS, and TCP traffic, supporting caching, load balancing, and traffic filtering.

## 🌐 Features

- ✅ Supports HTTP/HTTPS reverse proxy and forward proxy
- ✅ SSL/TLS termination and certificate management
- ✅ Load balancing with health checks
- ✅ Caching and compression for improved performance
- ✅ Access control and authentication integration with `ldap-server`
- ✅ Logging, metrics, and monitoring integration with `status-server` and `monitoring-server`
- ✅ Containerized and cloud-native deployment

## 📦 Part of the Zenth Cloud Stack

Zenth Proxy Server works in conjunction with:

- `ldap-server` – Authentication and access control
- `api-server` – Configuration and orchestration
- `status-server` / `monitoring-server` – Health monitoring and metrics
- `panel-server` – Administration interface
- `firewall-server` / `network-server` – Network policy enforcement

## 🛠️ Technology

- Based on a fork of well-known proxy projects like **NGINX**, **Traefik**, or **Envoy**
- Written in Go or C for high performance and extensibility
- Supports dynamic configuration via API

## 📖 Documentation

Comprehensive setup guides, configuration examples, and API documentation are available in `/docs` or on [Documentations](https://docs.zenthcloud.com).

## 🛡️ License

Zenth Proxy Server is licensed under the **GNU Affero General Public License v3 (AGPLv3)**. See the `LICENSE` file for details.

---

Contributions, bug reports, and feature requests are welcome at [github.com/zenthcloud](https://github.com/zenthcloud).
