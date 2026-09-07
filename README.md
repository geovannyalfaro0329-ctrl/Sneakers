# Sneakers
unit 7 
import Foundation

// MARK: - Part 1: Create a Brand Enumeration
enum SneakerBrand {
    case nike
    case adidas
    case jordan
    case newBalance
    case puma
}

// MARK: - Part 2: Create a Condition Enumeration
enum SneakerCondition {
    case new
    case excellent
    case good
    case fair
    case poor
}

// MARK: - Part 3: Create the Sneaker Structure
struct Sneaker {
    let name: String
    let brand: SneakerBrand
    let size: Double
    let condition: SneakerCondition
    let purchasedPrice: Double
    let estimatedValue: Double
}

// MARK: - Part 4: Create Three Sneakers
var sneaker1 = Sneaker(
    name: "Air Max 90",
    brand: .nike,
    size: 10.5,
    condition: .new,
    purchasedPrice: 130.0,
    estimatedValue: 150.0
)

var sneaker2 = Sneaker(
    name: "Ultraboost Light",
    brand: .adidas,
    size: 11.0,
    condition: .excellent,
    purchasedPrice: 190.0,
    estimatedValue: 160.0
)

var sneaker3 = Sneaker(
    name: "990v6",
    brand: .newBalance,
    size: 10.0,
    condition: .good,
    purchasedPrice: 200.0,
    estimatedValue: 180.0
)

