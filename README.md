The following a general plan for the Arches project. Be aware this plan is tentative and subject to change.


## Arches Roadmap

### 8.1 - Release date: March 2026
- User friendly resource identifiers
- Import and indexing of file metadata
- Global Arches Functions (triggered by tile crud events regardless of graph)
- RDM officially deprecated in favor of controlled lists (RDM remains available until v9.0)
- Deprecation of mapbox-gl.js 
- The following datatypes are deprecated (still available until 9.0)
    - concept
    - concept-list
    - domain
    - domain-list
- **Unfunded "Wishlist"**:
  - Improved customization of navigation UI
  - Allow for reference data type to replace concepts in defining resource relationships

### 8.2 (LTS) - Release date: March 2026
- **Unfunded "Wishlist"**:
  - Upgrade to Python 3.14
  - Upgrade rdflib to latest
  - Upgrade to Django 6
  - Upgrade to PostgreSQL 18
  - Upgrade to ElasticSearch 9
  - Improved support for user/group preferences
  - Graph edit log and history UI
  - Tools for building resource data migrations between graph versions
  - Single source of truth for tile display values, available at all tiers of the stack
  - Performance enhancements for loading large datasets

### 9.0 - Release date: September 2027
- Full migration to Vue
- Removal of the RDM
- Removal of the following datatypes:
    - concept
    - concept-list
    - domain
    - domain-list datatypes

### Possible Future Features (unfunded)
- Upgrade Django to version 6.0
- Allow reference items to define resource relationships
- Make main navigation bar configurable (e.g. add ability to remove/hide RDM)
- Add graph edit log (to support tile migrations)
- Require default value on required nodes (move default value config to node)
- Upgrade rdflib to allow support future Python versions

## Arches Lingo Roadmap

### 1.0 - Release date: March 2026

#### (Included in 1.0 alpha, released June 2025)

- Adds resource  models and controlled lists for managing thesauri and their terms as Arches resource data
- Introduces the Arches Lingo UI, a dedicated, custom experience for creating and managing thesauri and their terms including:
  - Hierarchy viewer for exploring thesauri hierarchically
  - Basic search for finding terms in thesauri
  - Basic Scheme and Concept reports and editors for editing thesauri and their terms

#### (Included in 1.0 beta, released September 2025)

- Improves the Arches Lingo UI with improved hierarchy viewer and search
- Extends the Scheme and Concept reports and editors with additional fields and features

#### (Coming in 1.0)

- Adds support for managing scheme and concept lifecycles including
  - Publishing schemes and their concepts to create new versions of schemes
  - Managing the automatic generation and assignment of friendly identifiers and URIs for schemes and concepts
  - Deprecating concepts and schemes
- Adds support for bulk import and export of thesauri and their terms as SKOS RDF
- Enhances the Lingo UI with user dashboards
- Advanced search and filtering capabilities for thesauri and their terms
- Allow users to view edit log for thesauri and their terms and revert changes as part of a draft edit
- Saved searches and search results for managing lists of terms 

### Possible Future Features (unfunded)

- Adds support for additional import/export formats
- Public search interface for searching over published thesauri and their terms even during draft edits
- SPARQL endpoint for querying thesauri and their terms
- Support for splitting and merging concepts within thesauri
- A "candidate scheme" for managing terms before they are added to a thesaurus
- Managing hierarchies of additional models:
  - People and groups
  - Places
  - Time periods

## Arches Modular Reports Roadmap

### 1.0 - Release Date: TBD

## Arches Controlled Lists Roadmap

### 1.1 - Release Date: March 2026
- Support loading of skos files during package load

### 1.2 - Release Date: September 2026
- **Unfunded "Wishlist"**:
  - Migrate domains and domain tile data to references/controlled lists
  - Improving Controlled List Manager UI for large datasets
  - Tools for synchronizing references across lists and in tile data

## Arches QuerySets Roadmap

### 1.1 - Release Date: TBD

## Arches Search Roadmap
- Postgresql fulltext search 
- Through resource advanced search

### 1.0 - Release Date: TBD

## Arches RaSColls Roadmap

### 1.0 - Release Date: TBD

## Arches for Science Roadmap

### 3.0 - Release Date: TBD


