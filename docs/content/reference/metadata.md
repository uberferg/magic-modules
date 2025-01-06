---
title: "MMv1 metadata reference"
weight: 35
---

# MMv1 metadata reference

This page documents all properties for metadata. Metadata does not impact the provider itself, but is used by Google internally for coverage metrics.

## Required

### `resource`

The name of the Terraform resource e.g., "google_cloudfunctions2_function".

### `generation_type`

The generation method used to create the Terraform resource e.g., "mmv1", "dcl", "handwritten".

## Optional

### `api_service_name`

The base name of the API used for this resource e.g., "cloudfunctions.googleapis.com".

### `api_version`

The version of the API used for this resource e.g., "v2".

### `api_resource_type_kind`

The API "resource type kind" used for this resource e.g., "Function".