# CSI-2300---Lab-4
MovieTest
classDiagram
    class Movie {
        -String title
        -String rating
        -int duration
        -int ticketsSold
        +Movie(title: String, rating: String, duration: int, ticketsSold: int)
        +getTitle(): String
        +getRating(): String
        +getDuration(): int
        +getTicketsSold(): int
        +setTitle(title: String): void
        +setRating(rating: String): void
        +setDuration(duration: int): void
        +setTicketsSold(ticketsSold: int): void
        +sellTickets(quantity: int): void
        +toString(): String
    }
    
    class MovieTest {
        +main(String[] args): void
    }
    
    MovieTest --> Movie : uses
![UML Diagram](https://github.com/user-attachments/assets/0d81be06-8fb2-43f0-856a-dc185c275296)
