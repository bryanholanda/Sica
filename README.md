# Sica — Sistema Casa Abrigo

**Historical academic team project · Java web application · 2012**

A preserved version of **Sistema Casa Abrigo**, a Java web application developed as a team project. The repository contains Maven configuration, web application sources, and the original team's project history.

## My recorded contribution

My contribution is narrower than the scope of the whole application. Commits recorded under **Bryan Fernandes** added the entity, data-access object, and controller for a **psychosocial-report deletion flow**:

| Change | Evidence |
| --- | --- |
| `RelatorioPsicoSocial` entity | [d81c8d4](https://github.com/bryanholanda/Sica/commit/d81c8d4d1b1fc65bf75fb60d9434bc759e10afe9) |
| `RelatorioPsicoSocialDAO` | [5db2af5](https://github.com/bryanholanda/Sica/commit/5db2af508c8241e254be3581d604647ddbbf70ab) |
| `RelatorioPsicoSocialController` | [1e84d66](https://github.com/bryanholanda/Sica/commit/1e84d66d579fb01b706e3a65eff7cd17766cc54b) |

These changes are preserved as a focused early contribution, not as evidence that I designed or implemented the entire system. The entity commit also records pair programming in the course context. No current end-to-end validation of this feature is claimed.

## Explore the repository

- [`src/`](src/) — application sources and resources.
- [`pom.xml`](pom.xml) — historical Maven project and dependency configuration.
- [`lib/`](lib/) — preserved supporting files.

## Maintenance status

No longer actively maintained. Compatibility with current Java versions, application servers, databases, and dependencies has not been verified. This documentation refresh does not alter the implementation or the original team history.

## Original project README

The original project description, credits, and changelog are retained below. The changelog describes the team's project, not my individual contribution.

---

Projeto Sica - Sistema Casa Abrigo V.0.2
=============================

Authors
-------
	Charles
	Caique
	Fernando
	Leonn	
	etc.

Changelog:
----------
	- 0.0.1 -
		CRUD Completo da Abrigada + css preeliminar e validação básica
	- 0.0.2-
		CRUD Completo Dependente + Abrigada
	- 0.0.3-
		CRUD Completo Abrigada + Dependente + Pertences - Relatório pendente

