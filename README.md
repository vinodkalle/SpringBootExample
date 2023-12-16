<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         List<Integer>nums=Arrays.asList(44,7,99,2,8,9);
		List<Integer>evennumbers=nums.stream().filter(a->a%2==0).collect(Collectors.toList());
		System.out.println("EvennumbersList"+evennumbers);
         
