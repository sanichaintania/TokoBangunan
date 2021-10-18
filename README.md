# TokoBangunan
Repositori pertama saya di GitHub
using System;
using System.Collections.Generic;
using System.Diagnostics;
using System.Linq;
using System.Threading.Tasks;
using Microsoft.AspNetCore.Mvc;
using Microsoft.Extensions.Logging;
using TokoBangunan.Models; 
using System.Text.Encodings.Web;

namespace TokoBangunan.Controllers
{
    public class TokoBangunan : Controller
    {

        public IActionResult Index()
        {
            return View();
        }

        public IActionResult Privacy()
        {
            return View();
        }
    }
}


@{ ViewData["Title"] = "Index" ; }
<h2> Selamat datang di website Toko Bangunan kami</h2>
<p> Kami disini menjual :</p>
<ul> 
    <li>Semen</li>
    <li>Batu bata</li>
    <li>Keramik</li>
    <li>Papan</li>
    <li>Kawat</li>
    <li>Keramik</li>
    <li>Pasir</li>
    
</ul>

