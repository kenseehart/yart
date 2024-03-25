# yart
Yet Another Rendering Tool

YART is a versatile, extensible drawing library designed to abstract away the complexities of image creation, asset management, and output generation, allowing users to focus on the content and design of their graphics. By handling various technical aspects internally, YART makes it easier to produce high-quality images, vector graphics, and documents without needing to manage the minutiae of asset dimensions or canvas sizes.

## Key Features

### Dimension-agnostic Design
YART is built with a philosophy that users shouldn't need to worry about the specific dimensions of assets or the canvas. Whether you're working with imported images or drawing shapes, YART ensures that everything scales harmoniously to the defined canvas size, keeping the creation process streamlined and intuitive.

### Center-focused Placement
Understanding that the most common requirement for placing objects is to have them centered, YART defaults to centered alignment. This approach simplifies the positioning of elements, making it straightforward to achieve balanced and aesthetically pleasing designs without additional effort.

### Versatile Output Formats
With support for PNG, SVG, and PDF output formats, YART provides flexibility in how the final graphics are used. Whether you need raster images for web and digital applications or vector graphics for print and detailed scaling, YART has you covered.

### Alpha Channel Transparency
Handling transparency, especially with the alpha channel, can be complex. YART simplifies this by ensuring that the alpha channel "just works" across all elements and assets, allowing for seamless integration of transparent images and effects.

### Extensibility
YART is designed to be super easy to extend by implenting new methods in your own Yart based class. Add atomic elements, compositions, and config parameters.

### YAML and JSON Support
Ease of use is a core tenet of YART, and this extends to its configuration and command structure. YART is designed to be easy to integrate with YAML and JSON handlers, allowing for the creation of graphics based on structured data formats. This makes it possible to define complex graphics through simple text files, streamlining the design process and enabling dynamic generation based on data.

## Future Improvements

### Justification Options
Future versions of YART will include the ability to specify text justification, with a default of center alignment. This will provide greater control over text layout and appearance, making it easier to achieve the desired visual effect.

### Named Assets
To further simplify the management of resources, YART plans to introduce named assets. This feature will allow users to reference assets by name rather than by file path, streamlining the design process and making templates more reusable.

### Nested Canvas
A nested canvas feature is also in the works, which will allow for more complex compositions by embedding one canvas within another. This will open up new possibilities for layering and composition in graphic designs.

### Markdown Extension
To integrate seamlessly with documentation and content creation workflows, YART is exploring the addition of a Markdown extension. This will allow graphics to be defined directly within Markdown files using a code block with a `language=yart` specifier, leveraging YAML syntax for commands. This feature will make it even easier to include dynamic, data-driven graphics in documents and online content.

YART continues to evolve, with a focus on making graphic creation accessible, flexible, and integrated with modern workflows.
