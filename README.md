# Ex09 Event Registration Web Application
## Date:08-10-2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
Home page

import React from "react";
import image1 from "./image-1.png";

export const Frame = () => {
  return (
    <div className="bg-white w-full min-w-[184px] min-h-[371px] relative">
      <img
        className="absolute top-1.5 left-0 w-[184px] h-[360px] aspect-[0.65] object-cover"
        alt="Image"
        src={image1}
      />

      <div className="absolute top-[247px] left-11 [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        a warm welcome
      </div>

      <p className="absolute top-[184px] left-[15px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        Bidding goodbye with love <br />
        and memories
      </p>

      <div className="absolute top-36 left-[27px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        {""}
      </div>

      <div className="absolute top-[103px] left-[17px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        FARWELL DAY CELEBRATION
      </div>

      <div className="absolute top-[137px] left-[77px] [font-family:'Inknut_Antiqua-Regular',Helvetica] font-normal text-black text-sm tracking-[0] leading-[normal]">
        2025
      </div>
    </div>
  );
};

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
@tailwind components;
@tailwind utilities;

@layer components {
  .all-\[unset\] {
    all: unset;
  }
}

:root {
  --animate-spin: spin 1s linear infinite;
}

.animate-fade-in {
  animation: fade-in 1s var(--animation-delay, 0s) ease forwards;
}

.animate-fade-up {
  animation: fade-up 1s var(--animation-delay, 0s) ease forwards;
}

.animate-marquee {
  animation: marquee var(--duration) infinite linear;
}

.animate-marquee-vertical {
  animation: marquee-vertical var(--duration) linear infinite;
}

.animate-shimmer {
  animation: shimmer 8s infinite;
}

.animate-spin {
  animation: var(--animate-spin);
}

@keyframes spin {
  to {
    transform: rotate(1turn);
  }
}

@keyframes image-glow {
  0% {
    opacity: 0;
    animation-timing-function: cubic-bezier(0.74, 0.25, 0.76, 1);
  }

  10% {
    opacity: 0.7;
    animation-timing-function: cubic-bezier(0.12, 0.01, 0.08, 0.99);
  }

  to {
    opacity: 0.4;
  }
}

@keyframes fade-in {
  0% {
    opacity: 0;
    transform: translateY(-10px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes fade-up {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes shimmer {
  0%,
  90%,
  to {
    background-position: calc(-100% - var(--shimmer-width)) 0;
  }

  30%,
  60% {
    background-position: calc(100% + var(--shimmer-width)) 0;
  }
}

@keyframes marquee {
  0% {
    transform: translate(0);
  }

  to {
    transform: translateX(calc(-100% - var(--gap)));
  }
}

@keyframes marquee-vertical {
  0% {
    transform: translateY(0);
  }

  to {
    transform: translateY(calc(-100% - var(--gap)));
  }
}

import React from "react";

export const Frame = () => {
  return (
    <div className="bg-white w-full min-w-[184px] min-h-[371px] relative">
      <div className="absolute top-[85px] left-[50px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        best wishes for
      </div>

      <div className="absolute top-[72px] left-[19px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        bes
      </div>

      <div className="absolute top-[97px] left-[39px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        hhhhh
      </div>
    </div>
  );
};

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};

@tailwind components;
@tailwind utilities;

@layer components {
  .all-\[unset\] {
    all: unset;
  }
}

:root {
  --animate-spin: spin 1s linear infinite;
}

.animate-fade-in {
  animation: fade-in 1s var(--animation-delay, 0s) ease forwards;
}

.animate-fade-up {
  animation: fade-up 1s var(--animation-delay, 0s) ease forwards;
}

.animate-marquee {
  animation: marquee var(--duration) infinite linear;
}

.animate-marquee-vertical {
  animation: marquee-vertical var(--duration) linear infinite;
}

.animate-shimmer {
  animation: shimmer 8s infinite;
}

.animate-spin {
  animation: var(--animate-spin);
}

@keyframes spin {
  to {
    transform: rotate(1turn);
  }
}

@keyframes image-glow {
  0% {
    opacity: 0;
    animation-timing-function: cubic-bezier(0.74, 0.25, 0.76, 1);
  }

  10% {
    opacity: 0.7;
    animation-timing-function: cubic-bezier(0.12, 0.01, 0.08, 0.99);
  }

  to {
    opacity: 0.4;
  }
}

@keyframes fade-in {
  0% {
    opacity: 0;
    transform: translateY(-10px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes fade-up {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes shimmer {
  0%,
  90%,
  to {
    background-position: calc(-100% - var(--shimmer-width)) 0;
  }

  30%,
  60% {
    background-position: calc(100% + var(--shimmer-width)) 0;
  }
}

@keyframes marquee {
  0% {
    transform: translate(0);
  }

  to {
    transform: translateX(calc(-100% - var(--gap)));
  }
}

@keyframes marquee-vertical {
  0% {
    transform: translateY(0);
  }

  to {
    transform: translateY(calc(-100% - var(--gap)));
  }
}

import React from "react";
import image3 from "./image-3.png";

export const Frame = () => {
  return (
    <div className="bg-white w-full min-w-[184px] min-h-[364px] relative">
      <img
        className="absolute top-0 left-0 w-[184px] h-[364px] aspect-[0.74] object-cover"
        alt="Image"
        src={image3}
      />

      <p className="absolute top-9 left-[18px] [font-family:'Irish_Grover-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        “goodbyes are not forever;
        <br />
        they are just the start of a<br />
        &nbsp;&nbsp;&nbsp;&nbsp;new journey”
      </p>
    </div>
  );
};

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};

@tailwind components;
@tailwind utilities;

@layer components {
  .all-\[unset\] {
    all: unset;
  }
}

:root {
  --animate-spin: spin 1s linear infinite;
}

.animate-fade-in {
  animation: fade-in 1s var(--animation-delay, 0s) ease forwards;
}

.animate-fade-up {
  animation: fade-up 1s var(--animation-delay, 0s) ease forwards;
}

.animate-marquee {
  animation: marquee var(--duration) infinite linear;
}

.animate-marquee-vertical {
  animation: marquee-vertical var(--duration) linear infinite;
}

.animate-shimmer {
  animation: shimmer 8s infinite;
}

.animate-spin {
  animation: var(--animate-spin);
}

@keyframes spin {
  to {
    transform: rotate(1turn);
  }
}

@keyframes image-glow {
  0% {
    opacity: 0;
    animation-timing-function: cubic-bezier(0.74, 0.25, 0.76, 1);
  }

  10% {
    opacity: 0.7;
    animation-timing-function: cubic-bezier(0.12, 0.01, 0.08, 0.99);
  }

  to {
    opacity: 0.4;
  }
}

@keyframes fade-in {
  0% {
    opacity: 0;
    transform: translateY(-10px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes fade-up {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes shimmer {
  0%,
  90%,
  to {
    background-position: calc(-100% - var(--shimmer-width)) 0;
  }

  30%,
  60% {
    background-position: calc(100% + var(--shimmer-width)) 0;
  }
}

@keyframes marquee {
  0% {
    transform: translate(0);
  }

  to {
    transform: translateX(calc(-100% - var(--gap)));
  }
}

@keyframes marquee-vertical {
  0% {
    transform: translateY(0);
  }

  to {
    transform: translateY(calc(-100% - var(--gap)));
  }
}

```


## OUTPUT:
![alt text](<Screenshot 2025-10-08 212200.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
