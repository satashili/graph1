# ThinkBeforeClick User Journey

## Individual User Journey (Free)

```mermaid
graph LR
    A[Landing Page] --> B[Click 'Start Now' for Individuals]
    B --> C[Registration/Login]
    C --> D[Email Verification]
    D --> E[Individual Dashboard]
    E --> F[Access Training Modules]
    F --> G[Watch Tutorials]
    G --> H[Review Scam Examples]
    H --> I[Complete Quizzes]
    I --> J[View Progress Report]
    J --> K{Continue Learning?}
    K -->|Yes| F
    K -->|No| L[Exit]
    
    style A fill:#667eea
    style E fill:#10B981
    style J fill:#F59E0B
```

## Enterprise User Journey (Paid)

```mermaid
graph LR
    A[Landing Page] --> B[Select 'Enterprise']
    B --> C[Enter Verification Code]
    C --> D[Registration Form]
    D --> E[Create Company ID + Org Type]
    E --> F[Email Verification]
    F --> G[Admin Login with Company ID]
    G --> H[Enterprise Dashboard]
    
    H --> I[Add Employees]
    I --> J[Select Phishing Templates]
    J --> K[Send Simulation Emails]
    K --> L[Real-Time Tracking]
    
    L --> M{Employee Opens Email?}
    M -->|Yes| N[Track Open Event]
    M -->|No| O[Email Not Opened]
    
    N --> P{Employee Clicks Link?}
    P -->|Yes| Q[Track Click Event]
    P -->|No| R[No Click Recorded]
    
    Q --> S[Redirect to Education Page]
    S --> T[Employee Learns Red Flags]
    
    L --> U[Generate Analytics Report]
    U --> V[View Metrics Dashboard]
    V --> W[- Open Rates<br>- Click Rates<br>- Employee Rankings<br>- Vulnerability Analysis]
    
    W --> X[Download Historical Reports]
    X --> Y{Run More Simulations?}
    Y -->|Yes| I
    Y -->|No| Z[Exit]
    
    style A fill:#667eea
    style H fill:#2563EB
    style U fill:#F59E0B
    style S fill:#10B981
    style W fill:#F59E0B
```

## Comparison Flow

```mermaid
graph LR
    A[ThinkBeforeClick Platform] --> B[Individual Path]
    A --> C[Enterprise Path]
    
    B --> D[Self-Learning<br>& Assessment]
    D --> E[Personal Progress<br>Tracking]
    
    C --> F[Employee Testing<br>& Simulation]
    F --> G[Vulnerability<br>Identification]
    G --> H[Targeted<br>Education]
    H --> I[Company-Wide<br>Analytics]
    
    style A fill:#667eea
    style B fill:#10B981
    style C fill:#2563EB
    style E fill:#10B981
    style I fill:#F59E0B
```

## Key Features by User Type

### Individual (FREE)
- ✅ Interactive training modules
- ✅ Adaptive quizzes
- ✅ Personal progress tracking
- ✅ Real-world scam examples
- ✅ Self-paced learning

### Enterprise (PAID)
- ✅ 10 phishing email templates
- ✅ Employee management system
- ✅ Real-time tracking (opens & clicks)
- ✅ Instant educational feedback
- ✅ Comprehensive analytics dashboard
- ✅ Vulnerability rankings
- ✅ Historical report downloads
- ✅ Template performance metrics

