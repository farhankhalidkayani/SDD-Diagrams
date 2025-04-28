erDiagram
    USERS ||--o{ USER_PROFILES : has
    USERS ||--o{ ADDRESSES : has
    USERS ||--o{ ITEMS : lists
    ITEMS }o--|| CATEGORIES : belongs_to
    ITEMS ||--o{ ITEM_IMAGES : has
    ITEMS ||--o{ BOOKINGS : receives
    USERS ||--o{ BOOKINGS : makes
    BOOKINGS ||--o{ PAYMENTS : generates
    PAYMENTS ||--|| TRANSACTIONS : creates
    ITEMS ||--o{ REVIEWS : receives
    USERS ||--o{ REVIEWS : writes
    USERS ||--o{ CONVERSATIONS : participates
    CONVERSATIONS ||--o{ MESSAGES : contains
    USERS ||--o{ NOTIFICATIONS : receives
    
    USERS {
        int userId PK
        string email
        string passwordHash
        string phone
        boolean isVerified
        datetime createDate
        enum userType
        enum status
    }
    
    USER_PROFILES {
        int profileId PK
        int userId FK
        string firstName
        string lastName
        date dateOfBirth
        string profilePicUrl
        string bio
        string gender
    }
    
    ADDRESSES {
        int addressId PK
        int userId FK
        string street
        string city
        string state
        string country
        string postalCode
        boolean isDefault
    }
    
    ITEMS {
        int itemId PK
        int userId FK
        string title
        string description
        decimal price
        decimal securityDeposit
        text rentalTerms
        json availability
        enum status
        datetime createdAt
        datetime updatedAt
    }
    
    ITEM_IMAGES {
        int imageId PK
        int itemId FK
        string imageUrl
        boolean isPrimary
        datetime uploadDate
    }
    
    CATEGORIES {
        int categoryId PK
        int parentId FK
        string name
        string description
    }
    
    BOOKINGS {
        int bookingId PK
        int itemId FK
        int renterId FK
        date startDate
        date endDate
        decimal totalAmount
        decimal securityDeposit
        enum status
        datetime createdAt
    }
    
    PAYMENTS {
        int paymentId PK
        int bookingId FK
        decimal amount
        string paymentMethod
        enum status
        datetime paymentDate
    }
    
    TRANSACTIONS {
        int transactionId PK
        int paymentId FK
        enum status
        datetime createdAt
        datetime updatedAt
        json metadata
    }
    
    REVIEWS {
        int reviewId PK
        int itemId FK
        int reviewerId FK
        int providerId FK
        int bookingId FK
        int rating
        text comment
        datetime createdAt
        enum status
    }
    
    CONVERSATIONS {
        int conversationId PK
        int user1Id FK
        int user2Id FK
        int itemId FK
        datetime lastMessageDate
        enum status
    }
    
    MESSAGES {
        int messageId PK
        int conversationId FK
        int senderId FK
        text content
        datetime sentAt
        boolean isRead
    }
    
    NOTIFICATIONS {
        int notificationId PK
        int userId FK
        enum type
        text content
        boolean isRead
        datetime createdAt
    }
