PdfRenderer
===========

This is a extention fo rails controller render

### Usage
    class HomeController < ApplicationController
      def index
        respond_to do |format|
          format.pdf { render :pdf => "contents" }
        end
      end
    end
