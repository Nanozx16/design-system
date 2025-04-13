# design-system
## **Description**

This PR fixes the dependency graph generation in the README.md by
correcting the relationships between packages. Previously, the graph was
showing incorrect dependencies, making every package appear as a
dependency of each other.

Specific changes:
1. Added correct dependency relationships
2. The dependency graph now accurately represents the actual package
relationships in the monorepo

This change ensures that the README's dependency graph is an accurate
representation of the project's package structure, making it easier for
developers to understand the relationships between different packages.

## **Related issues**

Fixes: N/A

## **Manual testing steps**

1. Run `yarn update-readme-content` to generate the updated dependency
graph
2. Verify that the new dependency relationships are correct

## **Screenshots/Recordings**

### **Before**
The dependency graph showed incorrect relationships between packages.
