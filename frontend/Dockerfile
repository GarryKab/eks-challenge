FROM awselscpt/frontend-base

COPY . .

RUN bundle install

EXPOSE 4567

CMD ["ruby", "app.rb"]

COPY . .
