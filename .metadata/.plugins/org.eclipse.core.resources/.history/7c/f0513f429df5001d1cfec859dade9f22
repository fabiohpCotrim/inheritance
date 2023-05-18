package entities;

import java.time.LocalDateTime;

public class UsedProduct extends Product{
	
	private LocalDateTime manufactureDate;
	
	public UsedProduct() {
	}

	public UsedProduct(String name, Double price, LocalDateTime manufactureDate) {
		super(name, price);
		this.manufactureDate = manufactureDate;
	}

	public LocalDateTime getManufactureDate() {
		return manufactureDate;
	}

	public void setManufactureDate(LocalDateTime manufactureDate) {
		this.manufactureDate = manufactureDate;
	}
	@Override
	public String priceTag() {
		return name 
				+ "(used) $" 
				+ String.format("%.2f", getPrice()) 
				+ "(Manufacture date: " + manufactureDate 
				+ ")";
	}

}
