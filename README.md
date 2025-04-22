// Mewzu Meme Coin Website Code // Tech: React + Tailwind CSS // Language: English

import React from "react"; import { Button } from "@/components/ui/button";

export default function HomePage() { return ( <div className="bg-black text-white min-h-screen font-sans"> <header className="py-10 px-6 text-center"> <h1 className="text-4xl md:text-6xl font-bold text-pink-400">Mewzu</h1> <p className="mt-4 text-xl md:text-2xl text-white"> The Cutest Meme Coin on Solana </p> <p className="mt-2 text-md md:text-lg text-gray-300"> Powered by paws. Backed by vibes. </p> <div className="mt-6 flex flex-col md:flex-row gap-4 justify-center"> <Button className="bg-pink-500 text-white px-6 py-3 rounded-full hover:bg-pink-600"> Buy $MEWZU </Button> <Button variant="outline" className="border-white text-white px-6 py-3 rounded-full hover:bg-white hover:text-black"> Join Community </Button> </div> </header>

<section className="bg-gradient-to-b from-black to-gray-900 px-6 py-12 text-center">
    <h2 className="text-3xl md:text-4xl font-semibold text-white mb-4">What is Mewzu?</h2>
    <p className="text-lg text-gray-300 max-w-2xl mx-auto">
      Mewzu is a meme coin on the Solana blockchain that blends internet culture with a passion for paws. It's cute, fast, and built for fun.
    </p>
  </section>

  <section className="px-6 py-12 text-center">
    <h2 className="text-3xl font-bold text-white mb-4">Tokenomics</h2>
    <ul className="text-lg text-gray-300 space-y-2">
      <li>Total Supply: 1,000,000,000 $MEWZU</li>
      <li>Team Allocation: 20%</li>
      <li>Liquidity & Community: 80%</li>
    </ul>
  </section>

  <section className="px-6 py-12 text-center bg-gray-950">
    <h2 className="text-3xl font-bold text-white mb-4">How to Buy</h2>
    <p className="text-lg text-gray-300 mb-4">
      You'll need a Solana wallet like Phantom or Solflare.
    </p>
    <Button className="bg-green-500 text-white px-6 py-3 rounded-full hover:bg-green-600">
      Coming Soon
    </Button>
  </section>

  <footer className="px-6 py-10 text-center text-gray-500 text-sm">
    © 2025 Mewzu. All rights reserved.
  </footer>
</div>

); }


