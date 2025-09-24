# ServiceNow ESC Styling Proof of Concept

## Project Context
This project serves as a proof-of-concept to demonstrate enhanced styling capabilities within ServiceNow's Employee Service Center (ESC) constraints. The goal is to showcase modern, high-fidelity UI design while strictly adhering to ESC's technical limitations.

## Technical Requirements

### Framework Constraints
- **Base Framework**: AngularJS (as required by ServiceNow ESC)
- **Deployment Platform**: Vercel
- **Styling Approach**: Using Angular-compatible UI libraries that provide unstyled, accessible components

### Key Considerations
1. **ESC Compatibility**: All components and styling must be implementable within ServiceNow ESC
2. **No Incompatible Features**: If a feature or styling approach cannot be implemented in ESC, it must not be included
3. **Modern UI**: Focus on achieving high-fidelity design within ESC constraints

## Development Guidelines

### Styling Libraries
- Using Angular-compatible UI libraries that provide unstyled, accessible components
- Focus on libraries that offer Radix UI / shadcn-like capabilities while maintaining ESC compatibility

### Component Development
1. Each component must be validated against ESC capabilities
2. Document any styling limitations or workarounds
3. Maintain accessibility standards
4. Use CSS approaches that are confirmed to work in ESC

### Testing Requirements
- Components must be tested in an environment that mirrors ESC constraints
- Document any performance implications of styling choices
- Validate responsive design within ESC

## Project Structure
```
/
├── src/
│   ├── app/
│   │   ├── components/    # Reusable UI components
│   │   ├── services/      # Angular services
│   │   └── styles/        # Global styles and themes
│   └── assets/           # Static assets
├── Ai/
│   └── agents.md         # This documentation file
└── README.md            # Project overview
```

## For Future AI Agents
1. Always verify any new features against ESC capabilities
2. Maintain documentation of styling decisions and their ESC compatibility
3. Keep track of any ServiceNow ESC updates that might affect styling capabilities
4. Document any workarounds or alternatives for desired features that aren't directly supported

## Resources
- [ServiceNow ESC Documentation](https://docs.servicenow.com/bundle/vancouver-platform-user-interface/page/build/service-portal/concept/employee-service-center.html)
- [AngularJS Development Guide](https://docs.angularjs.org/guide)
- [ServiceNow Community Portal](https://community.servicenow.com)

## Project Goals
1. Demonstrate modern styling capabilities within ESC
2. Provide a reference implementation for future ESC development
3. Document styling approaches that work within ESC constraints
4. Create reusable components that maintain high fidelity while respecting ESC limitations
