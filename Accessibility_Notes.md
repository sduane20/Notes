# HTML Accessibility WCAG 2.1

## Document Structure
- Page struction
    - Machine Readable Code
    - Landmarks (Header, Nav, etc)
- Content Structrure
    - Human Readable Code
    - Headings

- Use em's and rems for relative unit for zooming into the page if needed.

## List
- Ordered List
    - List of items in an order
- Unordered List
    - Generic listing of items in no specific order
- Description List
    - for FAQs, etc 

- Apart of 1.3.1 - Info and Relationships
    - Information, structure, and relationships conveyed through presentation can be programmatically determined or are available in text. 
    
## Navigation and Skip Links
 - Level AA 1.4.5 - Images of Text
    - If the technologies being used can achieve the visal presentation, text is used to convey information rahter than images of text.
- Level AA 3.2.3 - Consistent Navigation
    - Navigational mechanisms that are repeated on multiple Web Pages within a set of Web pages occur in the same relative order each time they are repeated, unless a change is initiated by the user. 
- Level AA 2.4.5 - Multiple Ways
    - More than one way is available to locate a Web page within a set of Web pages except where the Web Page is the result of, or a step in, a process.
- Level AA 3.2.4 - Consistent Identification
    - Components that have the same functionality within a set of Web pages are identified consistently.
-  Skip Link 
    - <a class="skip-link" href="#main">Skip to main</a>
    - Needs to be the first thing on the page after the header tag.
    - On main tag, add ID of "main " and tabindex of "-1".
- Skip Link CSS
    - .skip-link {
        left: -100%;
        position: absolute;
    }

    - .skip-link: focus {
        left: 50%;
    }


## Tables

## Forms, Focus, and Color Contrast

# Media

## Images

## Background Images via CSS

## SVG

## Audio

## Video

## Additional Media Guidelines

# Responsive Web Design and Accessibility

## Switch Context

## Order of Content/Focus

## Mobile Devices

## Additional Responsive Guidelines