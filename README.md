"use client";
import { useEffect, useState } from "react"; // React hooks
import {
  Abstraxion,
  useAbstraxionAccount,
  useModal
} from "@burnt-labs/abstraxion"; // Abstraxion-related hooks and components
import { Button } from "@burnt-labs/ui"; // Button component from the UI library
"use client";
import Link from "next/link"; // Import the Link component from Next.js
import { useState } from "react"; // Import the useState hook from React
import {
  Abstraxion,
  useAbstraxionAccount,
  useAbstraxionSigningClient,
} from "@burnt-labs/abstraxion"; // Import hooks and components related to Abstraxion
import { Button } from "@burnt-labs/ui"; // Import the Button component from the UI library
import "@burnt-labs/ui/dist/index.css"; // Import styles from the UI component library
import type { ExecuteResult } from "@cosmjs/cosmwasm-stargate"; // Import the ExecuteResult type
import { seatContractAddress } from "./layout"; // Import the contract address
