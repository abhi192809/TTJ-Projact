

## Table of contents

- [Link RuangAdmin](https://abhi192809.github.io/TTJ-Projact/)
- [Installation](#installation)
- [Usage](#usage)
- [License](#License)

## Installation 

**Here is how :** 

- Fork the repository
- Clone with ```git clone https://github.com/Codeigniter-Template/Ruang-Admin-Template.git```
- Or Download zip

## Usage 

<?php
defined('BASEPATH') or exit('No direct script access allowed');

class Dashboard extends CI_Controller
{
    public function index()
    {
        $this->load->view('dashboard/header');
        $this->load->view('dashboard/sidebar');
        $this->load->view('dashboard/topbar');
        $this->load->view('dashboard/index');
        $this->load->view('dashboard/footer');
    }
}
