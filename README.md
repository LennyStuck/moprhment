![image_alt](https://github.com/LennyStuck/moprhment/blob/main/img_readme.png)
# Morphment: Transforming Logos into Art
Welcome to Morphment, a pioneering collection of 1000 unique 3D NFTs that breathes life into the Movement Labs logo like you've never seen before. This isn't just a logo—it's a dynamic expression of art, where every piece tells its own story.

## About the Project
In the Morphment collection, the familiar Movement Labs logo transforms into a mesmerizing dance of textures and elements. Each NFT reveals a new aspect of the logo, blending materials in a way that captures the essence of movement and change. It's not just a static image; it's an experience, a journey through the creative process where every combination is thoughtfully crafted to be one-of-a-kind.

## The Structure
The magic of Morphment lies in its structure. We've divided the logo into three key elements:

Inner Core: The heart of the logo, available in iron, rock, wood, glass, gold, grass, brick, and cold materials.
Outer Shell: Encapsulating the core with the same diverse materials.
Side Frame: Adding depth and definition, also featuring the same material variety.
Background: Setting the stage with banana, columns, gods, or dark themes.
Each element is meticulously combined to create a unique visual experience, with every frame being a distinct expression of the logo.

## Code Overview
Here’s a glimpse into how we ensure each NFT is unique:
```python
def generate_unique_combination():
    return (
        weighted_choice([0.05, 0.05, 0.1, 0.1, 0.1, 0.15, 0.2, 0.25]),  
        weighted_choice([0.1, 0.1, 0.05, 0.2, 0.15, 0.05, 0.15, 0.2]),  
        weighted_choice([0.05, 0.05, 0.05, 0.05, 0.1, 0.2, 0.2, 0.3]),  
        weighted_choice([0.15, 0.25, 0.35, 0.25]) 
    )
```
This function ensures that no two frames are alike, making every piece in the Morphment collection a true original. The combination of elements is carefully weighted to balance variety with the aesthetic cohesion of the collection.

#### Metadata Generation
For every frame, metadata is automatically generated, encapsulating the unique attributes of each NFT. This metadata is crucial for platforms that support NFT collections, as it provides detailed information about the artwork, including the materials used for each element.

Feel free to use this as a base and adjust it according to your preferences!
