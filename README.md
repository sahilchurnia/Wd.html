import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { motion } from "framer-motion";

const photos = [
  {
    id: 1,
    title: "Golden Hour Bliss",
    imageUrl: "https://images.unsplash.com/photo-1506744038136-46273834b3fb",
    photographer: "Alice Smith",
  },
  {
    id: 2,
    title: "Urban Jungle",
    imageUrl: "https://images.unsplash.com/photo-1494526585095-c41746248156",
    photographer: "Bob Lee",
  },
  {
    id: 3,
    title: "Wildlife Majesty",
    imageUrl: "https://images.unsplash.com/photo-1508672019048-805c876b67e2",
    photographer: "Carla Rivera",
  },
];

export default function PhotographyMarketplace() {
  return (
    <main className="p-6 space-y-10">
      <header className="flex justify-between items-center">
        <h1 className="text-4xl font-bold">PhotoHaven</h1>
        <Button>Sign In</Button>
      </header>

      <section className="grid grid-cols-1 sm:grid-cols-2 md
