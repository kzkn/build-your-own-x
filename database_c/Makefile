db: main.c
	gcc -o$@ $<

.PHONY: test
test: db
	bundle exec rspec db_spec.rb
