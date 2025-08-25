import React, { useMemo, useRef, useState, useEffect } from "react";
import { motion } from "framer-motion";
import { 
  Github, Linkedin, Mail, Phone, MapPin, Download, ExternalLink, Link as LinkIcon,
  Globe, FolderGit2, User, Images, FileText, Sun, Moon, Send, Code2, Film, Camera,
  ChevronRight
} from "lucide-react";
import { Button } from "@/components/ui/button";
import { Card, CardHeader, CardContent, CardFooter } from "@/components/ui/card";
import { Badge } from "@/components/ui/badge";
import { Input } from "@/components/ui/input";
import { Textarea } from "@/components/ui/textarea";
import { Tabs, TabsList, TabsTrigger, TabsContent } from "@/components/ui/tabs";
import { Switch } from "@/components/ui/switch";

// =====================
// CONFIG — EDIT ME ONLY
// =====================
const PROFILE = {
  name: "Ansh Singh",
  role: "Full‑Stack Developer & Designer",
  location: "Delhi NCR, India",
  email: "you@example.com",
  phone: "+91-90000-00000",
 
