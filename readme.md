# Symfony Circular Relationships Serializer Groups

## Problem Statement

Handling circular relationships in Symfony when using the serializer can be challenging. In this solution, each entity, once set up, will have a group linked to the entity and a group for each property when you want to include an entity with another linked.

## Installation

1. Copy the "doctrine" folder along with the template to the root of your Symfony project.
2. Copy the custom command folder into the "src" directory of your Symfony project.

## Version 1.0

This version introduces a solution for managing circular relationships in Symfony when using the serializer.