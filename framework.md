# Conceptual Framework for Regional Adaptive Sustainable Design of Container-based Urban Smart Pavilions

```mermaid
flowchart TD
    subgraph FOUR_DIMENSIONS["Four Supporting Dimensions (Interactive Mechanism)"]
        direction LR
        REGIONAL_CONSTRAINTS["Regional Constraints"] <--> TECH_SYSTEM["Technical System"]
        TECH_SYSTEM <--> USER_NEEDS["User Needs"]
        USER_NEEDS <--> POLICY_SUPPORT["Policy Support"]
        POLICY_SUPPORT <--> REGIONAL_CONSTRAINTS
    end
    
    FOUR_DIMENSIONS --> CORE_GOAL["Core Goal<br>Regional Adaptive Sustainable Development"]
    
    CORE_GOAL --> SUSTAINABILITY["Three Dimensions of Sustainability"]
    
    subgraph SUSTAINABILITY["Three Dimensions of Sustainability"]
        direction LR
        ENV_SUSTAIN["<b>Environmental Sustainability</b><br>• Energy conservation & emission reduction<br>• Ecological protection<br>• Resource recycling"]
        ECO_SUSTAIN["<b>Economic Sustainability</b><br>• Cost control<br>• Operational efficiency<br>• Resource allocation"]
        SOC_SUSTAIN["<b>Social Sustainability</b><br>• User need fulfillment<br>• Cultural adaptation<br>• Social acceptance"]
    end
    
    subgraph OPERATION_MECHANISM["Closed-loop Operation Mechanism"]
        direction LR
        MODEL_BUILDING["<b>Model Building</b><br>Integrating four-dimensional elements"] 
        --> PERFORMANCE_VALIDATION["<b>Performance Validation</b><br>• Energy consumption simulation<br>• Spatial adaptability<br>• User evaluation"]
        --> OPTIMIZATION_FEEDBACK["<b>Optimization Feedback</b><br>Adjustment based on validation"]
        --> MODEL_BUILDING
    end
    
    SUSTAINABILITY --> OPERATION_MECHANISM
    
    %% Detailed Elements Expansion
    REGIONAL_CONSTRAINTS --> REGIONAL_DETAILS
    TECH_SYSTEM --> TECH_DETAILS
    USER_NEEDS --> USER_DETAILS
    POLICY_SUPPORT --> POLICY_DETAILS
    
    subgraph REGIONAL_DETAILS["Regional Constraint Elements"]
        CLIMATE["Climate Constraints<br>• Hot-humid in Sichuan Basin<br>• Vertical climate zones in Yunnan"]
        TOPOGRAPHY["Topography Constraints<br>• Complex mountainous areas<br>• Narrow spaces<br>• Dispersed settlements"]
        CULTURE["Cultural Constraints<br>• Yi/Bai/Tibetan ethnic cultures"]
    end
    
    subgraph TECH_DETAILS["Technical System Elements"]
        MODULAR["Modular Technology<br>• Split combination<br>• Staggered arrangement"]
        STRUCTURE["Structural Safety<br>• Seismic reinforcement<br>• Slope treatment"]
        ENERGY["Energy Efficiency<br>• Thermal insulation & moisture-proof<br>• Renewable energy"]
        SMART_TECH["Smart Operation<br>• IoT systems<br>• Intelligent monitoring"]
    end
    
    subgraph USER_DETAILS["User Need Elements"]
        FUNCTIONAL["Functional Needs<br>• Transportation connection<br>• Public services"]
        COMFORT["Comfort Needs<br>• Thermal comfort<br>• Accessibility"]
        CULTURAL_ADAPT["Cultural Needs<br>• Ethnic cultural adaptation"]
    end
    
    subgraph POLICY_DETAILS["Policy Support Elements"]
        URBAN_POLICY["Urban Renewal Policy"]
        SUSTAIN_POLICY["Sustainable Development Policy"]
        MODULAR_PROMO["Modular Construction Promotion"]
        LOCAL_CODES["Local Building Codes"]
    end
    
    %% Styling Definitions
    classDef core fill:#1e40af,stroke:#1e3a8a,color:#fff,font-size:16px
    classDef dimension fill:#3b82f6,stroke:#1d4ed8,color:#fff
    classDef sustainable fill:#60a5fa,stroke:#2563eb,color:#1e293b
    classDef mechanism fill:#93c5fd,stroke:#3b82f6,color:#1e293b
    classDef details fill:#dbeafe,stroke:#3b82f6,color:#1e293b,font-size:12px
    
    class CORE_GOAL core
    class REGIONAL_CONSTRAINTS,TECH_SYSTEM,USER_NEEDS,POLICY_SUPPORT dimension
    class ENV_SUSTAIN,ECO_SUSTAIN,SOC_SUSTAIN sustainable
    class MODEL_BUILDING,PERFORMANCE_VALIDATION,OPTIMIZATION_FEEDBACK mechanism
    class REGIONAL_DETAILS,TECH_DETAILS,USER_DETAILS,POLICY_DETAILS details
```

## Framework Description

### Core Elements
1. **Core Goal**: Regional Adaptive Sustainable Development
2. **Four Supporting Dimensions**:
   - Regional Constraints (Climate/Topography/Culture)
   - Technical System Optimization (Modular/Energy-efficient/Smart operation)
   - User Need Response (Functionality/Comfort/Cultural)
   - Policy Synergy Support (Policies/Codes/Promotion)
3. **Three Sustainability Dimensions**: Environmental, Economic, Social
4. **Operation Mechanism**: Model Building → Performance Validation → Optimization Feedback (closed-loop)

### Logical Relationships
The framework follows the "Constraints-Needs-Support-Optimization" logical chain, where all elements interact and influence each other to form an organic whole.

### Key Features
- **Regional Adaptability**: Specifically designed for Southwest China's geographical and cultural characteristics
- **Sustainable Integration**: Balances environmental, economic, and social sustainability
- **User-centered Design**: Responds to diverse user needs across different ethnic regions
- **Policy Alignment**: Supports and leverages existing urban development policies
```
