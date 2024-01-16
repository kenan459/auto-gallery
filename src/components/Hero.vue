<template>
  <!-- Section -->
  <div class="pt-[50px]">
    <!-- Container -->
    <div class="flex hero bg-cover bg-no-repeat h-[800px] text-white">
      <!-- Main Wrapper -->
      <div class="flex px-[50px] pt-[30px] gap-[50px] w-auto bg-gradient-to-r from-black/[0.8] from-0%">
        <div class="flex flex-col basis-1/2">
          <div class="flex gap-x-3">
            <div class="border-l-[6px] h-auto border-[#BB0000]"></div>
            <div class="text-[62px] font-black tracking-[3px]">
              #1 Sales Experience
            </div>
          </div>

          <div class="flex flex-col px-[20px]">
            <div class="text-[24px] font-black uppercase tracking-[3px]">
              Among Car shoppers nationwide
            </div>
            <div class="flex flex-col mt-8 gap-y-4">
              <Button
                class="text-[20px] h-[55px] w-[300px] p-2 border-[2px] border-white uppercase font-black tracking-[3px]"
                >Learn More</Button
              >
              <Button
                class="text-[20px] h-[55px] w-[300px] p-2 border-[2px] border-white uppercase font-black tracking-[3px]"
                >Contact Us</Button
              >
            </div>
          </div>
        </div>

        <div class="basis-[70%] py-3 px-[0px]">
          <div class="flex">
          <h4 class="text-[48px] font-black tracking-widest leading-[55px]">
            Excellence In Service, Customer Satisfaction Guaranteed! 
            <br>
            Trustworthy Reliability And High Quality Vehicles!
          </h4>
          </div>

          <p
            class="text-[20px] mt-[20px] py-[20px] px-[30px] text-white rounded-sm font-medium
             tracking-wider text-justify"
          >
            Weʼre a family-run dealership dedicated to bringing you closer to
            your dream car. With a passion for cars and a commitment to customer
            happiness, we make car buying simple and joyful. We believe in
            honesty, great deals, and helping you find the perfect ride. Join
            our car family today!
            <br>
            <span class="text-[22px] font-medium leading-[40px]"
              >-General Manager John Doe</span
            >
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.hero {
  background-image: url("../assets/hero.jpg");
  
}
</style>
