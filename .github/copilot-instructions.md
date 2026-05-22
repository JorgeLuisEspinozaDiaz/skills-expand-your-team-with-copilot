### School Overview

- The school name is "Mergington High School".
- It is a public high school in Mergington, Florida.
- The school motto is "Branch out and grow".
- The site primarily supports students and teachers managing school activities.

## Development Environment

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).

### User Interaction

Consider the following when communicating with the staff.

- The staff is not technical. Explain in simple terms as much as possible and avoid software jargon.
- Any new code must be easy to maintain and understand, without significant coding experience.

## Program architecture

- Keep the experience simple for students and teachers.
- Do not make additional apps or services.
- Do not make command line tools.
- Use an easy-to-understand directory structure instead of putting everything in one long file.
- Only use HTML, CSS, JavaScript, and Python.

## Useful commands

- Install dependencies: `pip install -r src/requirements.txt`
- Run the app locally: `python -m uvicorn src.app:app --host 0.0.0.0 --port 8000`
